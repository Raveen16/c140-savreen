## index.js
$('#bot_input_text').keypress(function(e){
        //If Enter key(key code is 13) pressed
        if(e.which == 13){         
            $('#send_button').click(); //Trigger Send Button Click Event
        }
    });



## app.py
response = {
            "bot_response": bot_res
        }

    return jsonify(response)