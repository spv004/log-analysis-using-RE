# log-analysis-using-RE

Sript that will process the system log and generate reports based on the information extracted from the log files.

This script will create the following reports:

    The ranking of errors generated by the system: A list of all the error messages logged and how many times each error was found, sorted by the most common error to the least common error. This report doesn't take into account the users involved.
    The user usage statistics for the service: A list of all users that have used the system, including how many info messages and how many error messages they've generated. This report is sorted by username.
