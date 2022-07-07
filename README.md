# linux-command
~$ cd
~$ cd -
/home/runner
~$ cd . .
bash: cd: too many arguments
~$ 
~$ mkdir -p groupd/chetan
~$ touch groupd/chetan/practice.txt
~$ git status
fatal: not a git repository (or any parent up to mount point /home)
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
~$ chomd
bash: chomd: command not found
~$ exit
exit
~/linux-command-3$ sudo/cd/root
bash: sudo/cd/root: No such file or directory
~/linux-command-3$ sudo cd/root/
bash: sudo: command not found
~/linux-command-3$ sudo cd /root/
bash: sudo: command not found
~/linux-command-3$ shutdown
bash: shutdown: command not found
~/linux-command-3$ shutdown now
bash: shutdown: command not found
~/linux-command-3$ shutdown -c
bash: shutdown: command not found
~/linux-command-3$ unzip
UnZip 6.00 of 20 April 2009, by Debian. Original by Info-ZIP.

Usage: unzip [-Z] [-opts[modifiers]] file[.zip] [list] [-x xlist] [-d exdir]
  Default action is to extract files in list, except those in xlist, to exdir;
  file[.zip] may be a wildcard.  -Z => ZipInfo mode ("unzip -Z" for usage).

  -p  extract files to pipe, no messages     -l  list files (short format)
  -f  freshen existing files, create none    -t  test compressed archive data
  -u  update files, create if necessary      -z  display archive comment only
  -v  list verbosely/show version info       -T  timestamp archive to latest
  -x  exclude files that follow (in xlist)   -d  extract files into exdir
modifiers:
  -n  never overwrite existing files         -q  quiet mode (-qq => quieter)
  -o  overwrite files WITHOUT prompting      -a  auto-convert any text files
  -j  junk paths (do not make directories)   -aa treat ALL files as text
  -U  use escapes for all non-ASCII Unicode  -UU ignore any Unicode fields
  -C  match filenames case-insensitively     -L  make (some) names lowercase
  -X  restore UID/GID info                   -V  retain VMS version numbers
  -K  keep setuid/setgid/tacky permissions   -M  pipe through "more" pager
  -O CHARSET  specify a character encoding for DOS, Windows and OS/2 archives
  -I CHARSET  specify a character encoding for UNIX and other archives

See "unzip -hh" or unzip.txt for more help.  Examples:
  unzip data1 -x joe   => extract all files except joe from zipfile data1.zip
  unzip -p foo | more  => send contents of foo.zip via pipe into program more
  unzip -fo foo ReadMe => quietly replace existing ReadMe if archive file newer
~/linux-command-3$ htop
bash: htop: command not found
~/linux-command-3$ sudo yum install gim
bash: sudo: command not found
~/linux-command-3$ sudo yum install gimb
bash: sudo: command not found
~/linux-command-3$ git sudo yum instll gimb
git: 'sudo' is not a git command. See 'git --help'.

The most similar command is
    submodule
~/linux-command-3$ eco 'cool message'
bash: eco: command not found
~/linux-command-3$ ps
    PID TTY          TIME CMD
   1276 pts/3    00:00:00 bash
   1600 pts/3    00:00:00 ps
~/linux-command-3$ ping google.com
bash: ping: command not found
~/linux-command-3$ vim
~/linux-command-3$ history
    1  cd
    2  clear
    3  ls
    4  ls
    5  cd
    6  cd -
    7  cd ...
    8  cd . .
    9  cp
   10  cp_file_to_copy.txt
   11  cp_file_to_readme.txt
   12  clear
   13  cd
   14  cd -
   15  cd . .
   16  cp
   17  cp_file_to_readme.txt readme.md
   18  cp
   19  rm
   20  mv
   21  clear
   22  cd
   23  cd -
   24  cd . .
   25  man mkdir
   26  mkdir -p  groupd/devops practice
   27  touch groupd/devops practice
   28  git status
   29  clear
   30  cd
   31  cd -
   32  cd . .
   33  mkdir -p groupd/chetan
   34  touch groupd/chetan/practice.txt
   35  git status
   36  chomd
   37  exit
   38  sudo/cd/root
   39  sudo cd/root/
   40  sudo cd /root/
   41  shutdown
   42  shutdown now
   43  shutdown -c
   44  unzip
   45  htop
   46  sudo yum install gim
   47  sudo yum install gimb
   48  git sudo yum instll gimb
   49  eco 'cool message'
   50  ps
   51  ping google.com
   52  vim
   53  history
~/linux-command-3$ which pyton
~/linux-command-3$ less
bash: less: command not found
~/linux-command-3$ less largest_text_readme.txt
bash: less: command not found
~/linux-command-3$ tail long.txt
tail: cannot open 'long.txt' for reading: No such file or directory
~/linux-command-3$ grep 'linux' long.txt
grep: long.txt: No such file or directory
~/linux-command-3$ whoami
runner
~/linux-command-3$ whatis
whatis what?
~/linux-command-3$ whatis pyton
pyton: nothing appropriate.
~/linux-command-3$ uname
Linux
~/linux-command-3$ neofetch
bash: neofetch: command not found
~/linux-command-3$ find
.
./.git
./.git/branches
./.git/branches/.keep
./.git/info
./.git/info/exclude
./.git/info/.keep
./.git/hooks
./.git/hooks/pre-receive.sample
./.git/hooks/update.sample
./.git/hooks/commit-msg.sample
./.git/hooks/pre-applypatch.sample
./.git/hooks/pre-commit.sample
./.git/hooks/fsmonitor-watchman.sample
./.git/hooks/applypatch-msg.sample
./.git/hooks/prepare-commit-msg.sample
./.git/hooks/post-update.sample
./.git/hooks/pre-rebase.sample
./.git/hooks/pre-push.sample
./.git/description
./.git/refs
./.git/refs/heads
./.git/refs/heads/main
./.git/refs/tags
./.git/refs/.keep
./.git/refs/remotes
./.git/refs/remotes/origin
./.git/refs/remotes/origin/main
./.git/objects
./.git/objects/pack
./.git/objects/info
./.git/objects/.keep
./.git/objects/59
./.git/objects/59/5028512456bc2e88c4ef6ea472fc5be17f7d6c
./.git/objects/69
./.git/objects/69/63511cfd4b034fec0c41819161fa73daa8715e
./.git/objects/ef
./.git/objects/ef/aa531369f69cdae1199290b33e397de975f4e7
./.git/objects/83
./.git/objects/83/8d79d69591420853e204a062c70927de11b555
./.git/objects/2a
./.git/objects/2a/ff877bf2f9f2a61c910f48c32fc5513c139751
./.git/objects/31
./.git/objects/31/eab82c5cef03e441f9d95c82a455f00e0281e6
./.git/objects/9c
./.git/objects/9c/b70eb30897a50898c06fec9245207a84c86cb3
./.git/objects/77
./.git/objects/77/37016481fd9dbdf0ec0d9145d56358fd71feb2
./.git/objects/e6
./.git/objects/e6/9de29bb2d1d6434b8b29ae775ad8c2e48c5391
./.git/objects/30
./.git/objects/30/4945ecf4d55ebcf07775a610a4b980e8c0b5df
./.git/objects/81
./.git/objects/81/f76e085f109966f8b367c456796e8ca269d6f0
./.git/objects/54
./.git/objects/54/86356334691f448aae766caf34b2244a5338f6
./.git/objects/00
./.git/objects/00/5e9e02d6393e6997525ba6cfc6bad1f903faee
./.git/FETCH_HEAD
./.git/logs
./.git/logs/refs
./.git/logs/refs/remotes
./.git/logs/refs/remotes/origin
./.git/logs/refs/remotes/origin/main
./.git/logs/refs/heads
./.git/logs/refs/heads/main
./.git/logs/HEAD
./.git/config
./.git/HEAD
./.git/index
./.git/ORIG_HEAD
./.replit
./groupd
./groupd/chetan
./groupd/chetan/readme.txt
./README.md
~/linux-command-3$ global config --global user.name 'chetan'
bash: global: command not found
~/linux-command-3$ git config --global user.name 'chetan'
~/linux-command-3$ git config --global user.name 'chetanmanakatti114@gmail.com'
~/linux-command-3$ git config --global -e
~/linux-command-3$ 
~/linux-command-3$ inux-command-2$ date
bash: inux-command-2$: command not found
~/linux-command-3$ Wed Jul  6 13:50:47 UTC 2022
bash: Wed: command not found
~/linux-command-3$ ~/linux-command-2$ cal
bash: /home/runner/linux-command-2$: No such file or directory
~/linux-command-3$      July 2022        
bash: July: command not found
~/linux-command-3$ Su Mo Tu We Th Fr Sa  
bash: Su: command not found
~/linux-command-3$                 1  2  
bash: 1: command not found
~/linux-command-3$  3  4  5  6  7  8  9  
bash: 3: command not found
~/linux-command-3$ 10 11 12 13 14 15 16  
bash: 10: command not found
~/linux-command-3$ 17 18 19 20 21 22 23  
bash: 17: command not found
~/linux-command-3$ 24 25 26 27 28 29 30  
bash: 24: command not found
~/linux-command-3$ 31                    
bash: 31: command not found
~/linux-command-3$ ~/linux-command-2$ ls
bash: /home/runner/linux-command-2$: No such file or directory
~/linux-command-3$ README.md
bash: README.md: command not found
~/linux-command-3$ ~/linux-command-2$ pwd
bash: /home/runner/linux-command-2$: No such file or directory
~/linux-command-3$ /home/runner/linux-command-2
bash: /home/runner/linux-command-2: No such file or directory
~/linux-command-3$ ~/linux-command-2$ 
bash: /home/runner/linux-command-2$: No such file or directory
~/linux-command-3$ ~/linux-command-2$ ls
bash: /home/runner/linux-command-2$: No such file or directory
~/linux-command-3$ README.md
bash: README.md: command not found
~/linux-command-3$ ~/linux-command-2$ pwd
bash: /home/runner/linux-command-2$: No such file or directory
~/linux-command-3$ /home/runner/linux-command-2
bash: /home/runner/linux-command-2: No such file or directory
~/linux-command-3$ ~/linux-command-2$ mkdir -p groupd/chetan
bash: /home/runner/linux-command-2$: No such file or directory
~/linux-command-3$ ~/linux-command-2$ git status
bash: /home/runner/linux-command-2$: No such file or directory
~/linux-command-3$ On branch main
bash: On: command not found
~/linux-command-3$ Your branch is up to date with 'origin/main'.
bash: Your: command not found
~/linux-command-3$ 
~/linux-command-3$ nothing to commit, working tree clean
bash: nothing: command not found
~/linux-command-3$ ~/linux-command-2$ touch groupd/chetan/readme.txt
bash: /home/runner/linux-command-2$: No such file or directory
~/linux-command-3$ ~/linux-command-2$ git status
bash: /home/runner/linux-command-2$: No such file or directory
~/linux-command-3$ On branch main
bash: On: command not found
~/linux-command-3$ Your branch is up to date with 'origin/main'.
bash: Your: command not found
~/linux-command-3$ 
~/linux-command-3$ Untracked files:
bash: Untracked: command not found
~/linux-command-3$   (use "git add <file>..." to include in what will be committed)
bash: use: command not found
~/linux-command-3$ 
~/linux-command-3$     groupd/
bash: groupd/: Is a directory
~/linux-command-3$ 
~/linux-command-3$ nothing added to commit but untracked files present (use "git add" to track)
bash: syntax error near unexpected token `('
~/linux-command-3$ git commit -m
error: switch `m' requires a value
usage: git commit [<options>] [--] <pathspec>...

    -q, --quiet           suppress summary after successful commit
    -v, --verbose         show diff in commit message template

Commit message options
    -F, --file <file>     read message from file
    --author <author>     override author for commit
    --date <date>         override date for commit
    -m, --message <message>
                          commit message
    -c, --reedit-message <commit>
                          reuse and edit message from specified commit
    -C, --reuse-message <commit>
                          reuse message from specified commit
    --fixup <commit>      use autosquash formatted message to fixup specified commit
    --squash <commit>     use autosquash formatted message to squash specified commit
    --reset-author        the commit is authored by me now (used with -C/-c/--amend)
    -s, --signoff         add Signed-off-by:
    -t, --template <file>
                          use specified template file
    -e, --edit            force edit of commit
    --cleanup <default>   how to strip spaces and #comments from message
    --status              include status in commit message template
    -S, --gpg-sign[=<key-id>]
                          GPG sign commit

Commit contents options
    -a, --all             commit all changed files
    -i, --include         add specified files to index for commit
    --interactive         interactively add files
    -p, --patch           interactively add changes
    -o, --only            commit only specified files
    -n, --no-verify       bypass pre-commit and commit-msg hooks
    --dry-run             show what would be committed
    --short               show status concisely
    --branch              show branch information
    --ahead-behind        compute full ahead/behind values
    --porcelain           machine-readable output
    --long                show status in long format (default)
    -z, --null            terminate entries with NUL
    --amend               amend previous commit
    --no-post-rewrite     bypass post-rewrite hook
    -u, --untracked-files[=<mode>]
                          show untracked files, optional modes: all, normal, no. (Default: all)
