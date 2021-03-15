# useful


Get your top 20 executed commands.
`history | sed -e 's/^ *[[:digit:]]* *//g' | sort | uniq -c  | sort -r | head -n20`
