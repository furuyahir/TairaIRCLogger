# TairaIRCLogger

To run:
  1. Install Python 2.7
  2. Open pyirclogs.py
  3. Change the Nickname field to what you want
  4. Run with python, or run build in sublime

To Do:
  * If person's username is mentioned, send them a ping email
  * Send them an email 30 minutes later with all the lines afterwards (and possibly some of the previous lines)
  * If the person is mentioned again before 30 minutes has passed:
      * do not resend the ping email
      * continue log until 30 minutes after most recent mention
  * Figure out best way to structure logged files based on this. Do we want to log everything? How often? What triggers new file creation?
  
