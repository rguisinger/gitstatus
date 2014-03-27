gitstatus
=========
Usage: git status-report [-e <email>][-d <days>]
Generates a status report for what you worked on for the past n days.
    -a, --all                        Displays output for all contributers sorted by person
    -b, --branches <branch name>     Limit results to work found in the specified branch(es). 
                                         Multiple branches can be comma separated
    -c, --current                    Generates status report for the current repo only
    -d, --days <num days>            The number of days to generate the report for. Defaults to past 6 days (one week)
    -e, --email <email address>      The email address of the committer to generate a report for. 
                                         Defaults to your "git config user.email" address. 
                                         Multiple email addresses can be comma separated.
    -f, --files                      Display a list of files involved in the commit(s)
    -h, --help                       Displays this message
    -r, --reverse                    Displays output in reverse chronological order
    -s, --simple                     Simpler output. Doesn't include the dates
    -v, --verbose                    Verbose output includes details on each 
