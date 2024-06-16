this directory contain executables scripts such as :

0-hello_world: echo "Hello, World"
1-confused_smiley: echo '"(Ôo)'\'
2-hellofile: cat /etc/passwd
3-twofiles: cat /etc/passwd /etc/hosts
4-lastlines: tail /etc/passwd
5-firstlines: head /etc/passwd
6-third_line: cat iacta | head -n 3 | tail -n 1
7-file: echo "Best School" > \\\*\\\\"'\"Best School\"\\'"\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\)
8-cwd_state: ls -la  > ls_cwd_content 
9-duplicate_last_line:  cat iacta | tail -n 1 >> iacta 
10-no_more_js: find . -type f -name  "*.js" -delete
11-directories : find . -type d ! -name . ! -name .. | wc -l
12-newest_files: find . -type f | ls -1t | head -10 
13-unique : cat | sort |uniq -u
14-findthatword : grep root /etc/passwd
15-countthatword: grep bin /etc/passwd | wc -l
16-whatsnext: grep -A3 root /etc/passwd 
17-hidethisword: grep -v bin /etc/passwd
18-letteronly: grep a /etc/ssh/sshd_config
19-AZ :tr "Ac" "Ze"
20-hiago: tr -d "cC"
21-reverse: rev
22-users_and_homes: cut -d: -f 1,6 /etc/passwd | sort