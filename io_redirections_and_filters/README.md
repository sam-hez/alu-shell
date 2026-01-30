I/O Redirections & Filters — brief

0-hello_world: prints "Hello, World"
1-confused_smiley: prints the confused smiley "(Ôo)'
2-hellofile: displays /etc/passwd
3-twofiles: displays /etc/passwd and /etc/hosts
4-lastlines: displays the last 10 lines of /etc/passwd
5-firstlines: displays the first 10 lines of /etc/passwd
6-third_line: displays the third line of file iacta (head | tail)
7-file: creates a special file named with many special chars and writes "Best School" into it
8-cwd_state: writes ls -la output into ls_cwd_content
9-duplicate_last_line: duplicates the last line of iacta
10-no_more_js: deletes regular .js files recursively (find -delete)
11-directories: counts directories and subdirectories (excluding .)
12-newest_files: prints 10 newest files in current directory
13-unique: prints words that appear exactly once (sort | uniq -u)
14-findthatword: prints lines with "root" from /etc/passwd
15-countthatword: prints count of lines with "bin" in /etc/passwd
16-whatsnext: prints lines containing "root" and 3 lines after them
17-hidethisword: prints lines that do NOT contain "bin"
18-letteronly: prints lines in /etc/ssh/sshd_config starting with a letter
19-AZ: replace 'A'->'Z' and 'c'->'e' using tr
20-hiago: removes letters c and C from input using tr -d
21-reverse: reverses input using rev
22-users_and_homes: lists users and their home directories, sorted
23-empty_casks: finds empty files and directories and prints their names
24-gifs: lists .gif files (names without extension), case-insensitive sorted
25-acrostic: decodes acrostics by taking first letters and uppercase using perl
26-the_biggest_fan: prints top 11 hosts by request count from TSV input
