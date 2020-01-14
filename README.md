# Lab 3

## Setup
* First, stop your nginx service if it is still running: <code>sudo systemctl stop nginx</code>
* Then, install docker compose (a tool that manages multiple docker containers): <code>sudo apt install docker-compose</code>
* Clone this git repository: <code>git clone https://github.com/prog38263/lab3.git</code>
* Change into the root of the lab directory, where the docker-compose.yaml file is located: <code>cd lab3</code>
* Run the docker-compose command, which builds and starts the containers in the compose file: <code>sudo docker-compose up</code>
* The compose file should have started an nginx web server with PHP (https://www.php.net/) support.
* Browse to the IP address of your server.
* You can stop the docker containers by hitting <code>ctrl + c</code> in the terminal where you started docker.

## Experimenting
* The code for the example can be found in the <cod>code</code> folder in the repository.
* Edit the <code>index.php</code> to add a for loop that prints the numbers from 1-10. For reference, check out these PHP links:
  * <https://www.w3schools.com/php/php_echo_print.asp>
  * <https://www.w3schools.com/php/php_if_else.asp>
  * <https://www.w3schools.com/php/php_looping.asp>
* Experiment and try out some of the PHP tutorials found here: <https://www.w3schools.com/php/>
* See if you can create a PHP script that presents a simple form to the user. The form should contain a single text box. When the form is submitted, you should echo the textbox contents back to the user. <https://www.w3schools.com/php/php_forms.asp>

## Solutions
* Check the <solutions> folder in this repository for solutions to the two exercises above.
