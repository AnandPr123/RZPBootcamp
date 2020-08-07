# RZPBootcamp
1. QuizGame
   - To run the Quizgame, clone this repository and execute the below command in terminal.
      ```sh
          $ go run main.go -csv="csvFileName" -limit="timeLimitForGameInSec"
          
2. URLShortener
   - To run the URLShortener, clone this repository and execute the below command in terminal.
      ```sh
          $ go run main.go 
        
      
3. CLI_Task_Manager
   - To run the CLI_Task_Manager, clone this repository and execute the below command in terminal.
      ```sh
          $ go build .
          $ ./task
   - To add a new task to the TODO list
      ```sh
          $ ./task add "TaskToAdd"
   - To mark a task on the TODO list as complete
      ```sh
          $ ./task do "TaskNumber"
   - To list all of the incomplete tasks
       ```sh
          $ ./task list
