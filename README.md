# scripts

Task 1 - create a script wikipython that reads a Wikipedia page - https://en.wikipedia.org/wiki/Python_(genus) (use curl command)

    extracts Species elements - python name (what kind of pythons are there) - use grep
    save the output the to new file
    append to the new file the last line that is the count of species - using wc

Task 2 - create a script weather that give you the weather from curl https://wttr.in/(location)

    the location will be read from the keyboard - example weather Bucharest
    test that you have the location
    test that location is a valid string and doesn't contain numbers using a regex operator compare a variable with $var =~ '^[0-9]+$'

Task 3 - create a health check script healthCheck that looks at:

    date and time
    the uptime of the machine
    how much disk df and memory usage free
    top most expensive process
    run this every 2 seconds using sleep or watch

Task 4 - create a script that reads the file data/ip.txt and:

    Find out how many different IPs?
    How many exit different codes?
    How many occurrences of each exit code?
    How often an IP appears?
    Which IP has experienced the most successes and failures?

Task 5 - create a script that reads the file data/hadoop.log and:

    Find out how many INFO, WARN ERROR messages are, print the percentage compared to total lines
    Which error appears most frequently?
    Are there any weird messages in the log?
