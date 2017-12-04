# rest-app

Set up the app by running `bundle install` in the command line. Then enter `ruby server.rb` to run the app.

Open the app at http://localhost:4567/


Use the following example requests in the command line to practice using curl requests:
* For a `GET` request for all messages, enter  `curl --request GET http://localhost:4567/messages`
* For a `GET` request for a single message (the seventh in this case, enter `curl --request GET http://localhost:4567/messages/7`
* For a `POST` request, enter `curl --request POST http://localhost:4567/messages --data "message=your message, here"`
* For a `PATCH` request, enter `curl --request PATCH http://localhost:4567/messages/1 --data "message=I am number one thousand"`
* For a `DELETE` request, entert `curl --request DELETE http://localhost:4567/messages/25`

Running `ruby weather.rb` will use a GET request from an external website to display the current weather for Boston in the terminal.
