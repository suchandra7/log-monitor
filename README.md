Log System:
->Clone the entire repo to your local.
->open terminal/command-prompt and point to the cloned folders path.
->Create an empty folder to store the logs (if doesn't exists).
->copy the path of the logs folder where you want the program to create logs, which will be the substitution for the DATA_PATH mentioned in the below commands.
->run the command "./generate.sh DATA_PATH"
->The above command will generate 1000 logs in DATA_PATH folder for the date(2014-10-31).
->Then run the command "./query.sh DATA_PATH", which will prompt a interactive query tool which expects for the two possible commands as mentioned below.
->In the interactive tool provide the command "QUERY IP cpu_id time_start time_end" to filter IPs between start and end time. eg.QUERY 192.168.1.12 0 2014-10-31 00:00 2014-10-31 00:05
->In the interactive tool provide the command "EXIT"(all capitals) to exit from the interactive tool.
