# Overthewire
Learn Hacking from Scratch

<h2>Bandit Level 0</h2>
<h3>Level Goal: </h3>
<p>The password for the next level is stored in a file called readme located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.</p>
<table>
<thead>
<tr>
<th>Host</th>
<th>Port</th>
<th>Password</th>
</tr>
</thead>
<tbody>
<tr>
<td>bandit0@bandit.labs.overthewire.org</td>
<td>2220</td>
<td>bandit0</td>
</tr>
</tbody>
</table>
<h3>Kali Commands: </h3>
<h3>Information: </h3>
<p>First, if you know a command, but don’t know how to use it, try the manual (man page) by entering “man <command>” (without the quotes). e.g. if you know about the “ls” command, type: man ls. The “man” command also has a manual, try it. Press q to quit the man command. if you havent installed man, just install it with apt-get install man.
Second, if there is no man page, the command might be a shell built-in. In that case use the “help <X>” command. E.g. help cd
Also, your favorite search-engine is your friend. Learn how to use it! I recommend DuckDuckGo.</p>
<table>
<thead>
<tr>
<th>Command</th>
<th>Synopsis</th>
<th>Description</th>
<th>Options</th>
</tr>
</thead>
<tbody>
<tr>
<td>ls</td>
<td>ls [OPTION]... [FILE]...</td>
<td>List  information  about the FILEs (the current directory by default).  Sort entries alphabetically if none of
  -cftuvSUX nor --sort is specified.</td>
<td>-a, -A, --author. -b, --block-size=SIZE</td>
</tr>
<tr>
<td>cd</td>
<td>cd [-L|[-P [-e]] [-@]] [dir]</td>
<td>Change the current directory to DIR. The default DIR is the value of the HOME shell variable.</td>
<td>-L, -P, -e, -@</td>
</tr>
<tr>
<td>cat</td>
<td>cat [OPTION]... [FILE]...</td>
<td>Concatenate files and print on the standard output.</td>
<td>-A, -b, -e, -E, -n, -s</td>
</tr>
<tr>
<td>file</td>
<td>file [-bcdEhiklLNnprsSvzZ0] [--apple] [--extension] [--mime-encoding] [--mime-type] [-e testname] [-F separator]
          [-f namefile] [-m magicfiles] [-P name=value] file ... 
  file -C [-m magicfiles]
  file [--help]</td>
<td>Determine file type.</td>
<td>--apple, --extension, --mime-encoding, --mime-type, -e testname, -F separator, [-f namefile], -m magicfiles, -P name=value</td>
</tr>
<tr>
<td>du</td>
<td>du [OPTION]... [FILE]...
       du [OPTION]... --files0-from=F</td>
<td>Estimate file space usage.</td>
<td>-0, -a, -apparent-size, -B, -b</td>
</tr>
<tr>
<td>find</td>
<td>find [-H] [-L] [-P] [-D debugopts] [-Olevel] [starting-point...] [expression]</td>
<td>Search for files in a directory hierarchy</td>
<td>-H, -L, -P, -D, -Olevel, starting-point</td>
</tr>
</tbody>
</table>

<h2>Bandit Level 1</h2>
<h3>Level Goal: </h3>
<p>The password for the next level is stored in a file called - located in the home directory, find it</p>
<table>
<thead>
<tr>
<th>Host</th>
<th>Port</th>
<th>Password</th>
</tr>
</thead>
<tbody>
<tr>
<td>bandit1@bandit.labs.overthewire.org</td>
<td>2220</td>
<td>boJ9jbbUNNfktd78OOpsqOltutMc3MY1</td>
</tr>
</tbody>
</table>
<h3>Kali Commands: </h3>
<h3>Information: </h3>
<p>First, if you know a command, but don’t know how to use it, try the manual (man page) by entering “man <command>” (without the quotes). e.g. if you know about the “ls” command, type: man ls. The “man” command also has a manual, try it. Press q to quit the man command. if you havent installed man, just install it with apt-get install man.
Second, if there is no man page, the command might be a shell built-in. In that case use the “help <X>” command. E.g. help cd
Also, your favorite search-engine is your friend. Learn how to use it! I recommend DuckDuckGo.</p>
<table>
<thead>
<tr>
<th>Command</th>
<th>Synopsis</th>
<th>Description</th>
<th>Options</th>
</tr>
</thead>
<tbody>
<tr>
<td>ls</td>
<td>ls [OPTION]... [FILE]...</td>
<td>List  information  about the FILEs (the current directory by default).  Sort entries alphabetically if none of
  -cftuvSUX nor --sort is specified.</td>
<td>-a, -A, --author. -b, --block-size=SIZE</td>
</tr>
<tr>
<td>cd</td>
<td>cd [-L|[-P [-e]] [-@]] [dir]</td>
<td>Change the current directory to DIR. The default DIR is the value of the HOME shell variable.</td>
<td>-L, -P, -e, -@</td>
</tr>
<tr>
<td>cat</td>
<td>cat [OPTION]... [FILE]...</td>
<td>Concatenate files and print on the standard output.</td>
<td>-A, -b, -e, -E, -n, -s</td>
</tr>
<tr>
<td>file</td>
<td>file [-bcdEhiklLNnprsSvzZ0] [--apple] [--extension] [--mime-encoding] [--mime-type] [-e testname] [-F separator]
          [-f namefile] [-m magicfiles] [-P name=value] file ... 
  file -C [-m magicfiles]
  file [--help]</td>
<td>Determine file type.</td>
<td>--apple, --extension, --mime-encoding, --mime-type, -e testname, -F separator, [-f namefile], -m magicfiles, -P name=value</td>
</tr>
<tr>
<td>du</td>
<td>du [OPTION]... [FILE]...
       du [OPTION]... --files0-from=F</td>
<td>Estimate file space usage.</td>
<td>-0, -a, -apparent-size, -B, -b</td>
</tr>
<tr>
<td>find</td>
<td>find [-H] [-L] [-P] [-D debugopts] [-Olevel] [starting-point...] [expression]</td>
<td>Search for files in a directory hierarchy</td>
<td>-H, -L, -P, -D, -Olevel, starting-point</td>
</tr>
</tbody>
</table>
<h3>Helpful Reading Material</h3>
<p><a href="https://duckduckgo.com/?q=dashed+filename&atb=v258-2__&ia=web" target="_blank">DuckDuckGo Search for “dashed filename”</a></p>
<p><a href="http://tldp.org/LDP/abs/html/special-chars.html" target="_blank">Advanced Bash-scripting Guide - Chapter 3 - Special Characters</a></p>

<h2>Bandit Level 2</h2>
<h3>Level Goal: </h3>
<p>The password for the next level is stored in a file called <strong>spaces in this filename</strong> located in the home directory</p>
<table>
<thead>
<tr>
<th>Host</th>
<th>Port</th>
<th>Password</th>
</tr>
</thead>
<tbody>
<tr>
<td>bandit2@bandit.labs.overthewire.org</td>
<td>2220</td>
<td>CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9</td>
</tr>
</tbody>
</table>
<h3>Kali Commands: </h3>
<h3>Information: </h3>
<p>First, if you know a command, but don’t know how to use it, try the manual (man page) by entering “man <command>” (without the quotes). e.g. if you know about the “ls” command, type: man ls. The “man” command also has a manual, try it. Press q to quit the man command. if you havent installed man, just install it with apt-get install man.
Second, if there is no man page, the command might be a shell built-in. In that case use the “help <X>” command. E.g. help cd
Also, your favorite search-engine is your friend. Learn how to use it! I recommend DuckDuckGo.</p>
<table>
<thead>
<tr>
<th>Command</th>
<th>Synopsis</th>
<th>Description</th>
<th>Options</th>
</tr>
</thead>
<tbody>
<tr>
<td>ls</td>
<td>ls [OPTION]... [FILE]...</td>
<td>List  information  about the FILEs (the current directory by default).  Sort entries alphabetically if none of
  -cftuvSUX nor --sort is specified.</td>
<td>-a, -A, --author. -b, --block-size=SIZE</td>
</tr>
<tr>
<td>cd</td>
<td>cd [-L|[-P [-e]] [-@]] [dir]</td>
<td>Change the current directory to DIR. The default DIR is the value of the HOME shell variable.</td>
<td>-L, -P, -e, -@</td>
</tr>
<tr>
<td>cat</td>
<td>cat [OPTION]... [FILE]...</td>
<td>Concatenate files and print on the standard output.</td>
<td>-A, -b, -e, -E, -n, -s</td>
</tr>
<tr>
<td>file</td>
<td>file [-bcdEhiklLNnprsSvzZ0] [--apple] [--extension] [--mime-encoding] [--mime-type] [-e testname] [-F separator]
          [-f namefile] [-m magicfiles] [-P name=value] file ...
  file -C [-m magicfiles]
  file [--help]</td>
<td>Determine file type.</td>
<td>--apple, --extension, --mime-encoding, --mime-type, -e testname, -F separator, [-f namefile], -m magicfiles, -P name=value</td>
</tr>
<tr>
<td>du</td>
<td>du [OPTION]... [FILE]...
       du [OPTION]... --files0-from=F</td>
<td>Estimate file space usage.</td>
<td>-0, -a, -apparent-size, -B, -b</td>
</tr>
<tr>
<td>find</td>
<td>find [-H] [-L] [-P] [-D debugopts] [-Olevel] [starting-point...] [expression]</td>
<td>Search for files in a directory hierarchy</td>
<td>-H, -L, -P, -D, -Olevel, starting-point</td>
</tr>
</tbody>
</table>
<h3>Helpful Reading Material</h3>
<p><a href="https://duckduckgo.com/?q=spaces+in+filename&atb=v258-2__&ia=web">DuckDuckGo Search for “spaces in filename”</a></p>

<h2>Bandit Level 3</h2>
<h3>Level Goal: </h3>
<p>The password for the next level is stored in a hidden file in the <strong>inhere</strong> directory.</p>
<table>
<thead>
<tr>
<th>Host</th>
<th>Port</th>
<th>Password</th>
</tr>
</thead>
<tbody>
<tr>
<td>bandit3@bandit.labs.overthewire.org</td>
<td>2220</td>
<td>UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK</td>
</tr>
</tbody>
</table>
<h3>Kali Commands: </h3>
<h3>Information: </h3>
<p>First, if you know a command, but don’t know how to use it, try the manual (man page) by entering “man <command>” (without the quotes). e.g. if you know about the “ls” command, type: man ls. The “man” command also has a manual, try it. Press q to quit the man command. if you havent installed man, just install it with apt-get install man.
Second, if there is no man page, the command might be a shell built-in. In that case use the “help <X>” command. E.g. help cd
Also, your favorite search-engine is your friend. Learn how to use it! I recommend DuckDuckGo.</p>
<table>
<thead>
<tr>
<th>Command</th>
<th>Synopsis</th>
<th>Description</th>
<th>Options</th>
</tr>
</thead>
<tbody>
<tr>
<td>ls</td>
<td>ls [OPTION]... [FILE]...</td>
<td>List  information  about the FILEs (the current directory by default).  Sort entries alphabetically if none of
  -cftuvSUX nor --sort is specified.</td>
<td>-a, -A, --author. -b, --block-size=SIZE</td>
</tr>
<tr>
<td>cd</td>
<td>cd [-L|[-P [-e]] [-@]] [dir]</td>
<td>Change the current directory to DIR. The default DIR is the value of the HOME shell variable.</td>
<td>-L, -P, -e, -@</td>
</tr>
<tr>
<td>cat</td>
<td>cat [OPTION]... [FILE]...</td>
<td>Concatenate files and print on the standard output.</td>
<td>-A, -b, -e, -E, -n, -s</td>
</tr>
<tr>
<td>file</td>
<td>file [-bcdEhiklLNnprsSvzZ0] [--apple] [--extension] [--mime-encoding] [--mime-type] [-e testname] [-F separator]
          [-f namefile] [-m magicfiles] [-P name=value] file ...
  file -C [-m magicfiles]
  file [--help]</td>
<td>Determine file type.</td>
<td>--apple, --extension, --mime-encoding, --mime-type, -e testname, -F separator, [-f namefile], -m magicfiles, -P name=value</td>
</tr>
<tr>
<td>du</td>
<td>du [OPTION]... [FILE]...
       du [OPTION]... --files0-from=F</td>
<td>Estimate file space usage.</td>
<td>-0, -a, -apparent-size, -B, -b</td>
</tr>
<tr>
<td>find</td>
<td>find [-H] [-L] [-P] [-D debugopts] [-Olevel] [starting-point...] [expression]</td>
<td>Search for files in a directory hierarchy</td>
<td>-H, -L, -P, -D, -Olevel, starting-point</td>
</tr>
</tbody>
</table>

<h2>Bandit Level 4</h2>
<h3>Level Goal: </h3>
<p>The password for the next level is stored in the only human-readable file in the <strong>inhere</strong> directory. Tip: if your terminal is messed up, try the “reset” command.</p>
<table>
<thead>
<tr>
<th>Host</th>
<th>Port</th>
<th>Password</th>
</tr>
</thead>
<tbody>
<tr>
<td>bandit4@bandit.labs.overthewire.org</td>
<td>2220</td>
<td>pIwrPrtPN36QITSp3EQaw936yaFoFgAB</td>
</tr>
</tbody>
</table>
<h3>Kali Commands: </h3>
<h3>Information: </h3>
<p>First, if you know a command, but don’t know how to use it, try the manual (man page) by entering “man <command>” (without the quotes). e.g. if you know about the “ls” command, type: man ls. The “man” command also has a manual, try it. Press q to quit the man command. if you havent installed man, just install it with apt-get install man.
Second, if there is no man page, the command might be a shell built-in. In that case use the “help <X>” command. E.g. help cd
Also, your favorite search-engine is your friend. Learn how to use it! I recommend DuckDuckGo.</p>
<table>
<thead>
<tr>
<th>Command</th>
<th>Synopsis</th>
<th>Description</th>
<th>Options</th>
</tr>
</thead>
<tbody>
<tr>
<td>ls</td>
<td>ls [OPTION]... [FILE]...</td>
<td>List  information  about the FILEs (the current directory by default).  Sort entries alphabetically if none of
  -cftuvSUX nor --sort is specified.</td>
<td>-a, -A, --author. -b, --block-size=SIZE</td>
</tr>
<tr>
<td>cd</td>
<td>cd [-L|[-P [-e]] [-@]] [dir]</td>
<td>Change the current directory to DIR. The default DIR is the value of the HOME shell variable.</td>
<td>-L, -P, -e, -@</td>
</tr>
<tr>
<td>cat</td>
<td>cat [OPTION]... [FILE]...</td>
<td>Concatenate files and print on the standard output.</td>
<td>-A, -b, -e, -E, -n, -s</td>
</tr>
<tr>
<td>file</td>
<td>file [-bcdEhiklLNnprsSvzZ0] [--apple] [--extension] [--mime-encoding] [--mime-type] [-e testname] [-F separator]
          [-f namefile] [-m magicfiles] [-P name=value] file ...
  file -C [-m magicfiles]
  file [--help]</td>
<td>Determine file type.</td>
<td>--apple, --extension, --mime-encoding, --mime-type, -e testname, -F separator, [-f namefile], -m magicfiles, -P name=value</td>
</tr>
<tr>
<td>du</td>
<td>du [OPTION]... [FILE]...
       du [OPTION]... --files0-from=F</td>
<td>Estimate file space usage.</td>
<td>-0, -a, -apparent-size, -B, -b</td>
</tr>
<tr>
<td>find</td>
<td>find [-H] [-L] [-P] [-D debugopts] [-Olevel] [starting-point...] [expression]</td>
<td>Search for files in a directory hierarchy</td>
<td>-H, -L, -P, -D, -Olevel, starting-point</td>
</tr>
</tbody>
</table>

<h2>Bandit Level 5</h2>
<h3>Level Goal: </h3>
<p>The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties: </p>
<ul>
<li>human-readable</li>
<li>1033 bytes in size</li>
<li>not executable</li>
</ul>
<table>
<thead>
<tr>
<th>Host</th>
<th>Port</th>
<th>Password</th>
</tr>
</thead>
<tbody>
<tr>
<td>bandit5@bandit.labs.overthewire.org</td>
<td>2220</td>
<td>koReBOKuIDDepwhWk7jZC0RTdopnAYKh</td>
</tr>
</tbody>
</table>
<h3>Kali Commands: </h3>
<h3>Information: </h3>
<p>First, if you know a command, but don’t know how to use it, try the manual (man page) by entering “man <command>” (without the quotes). e.g. if you know about the “ls” command, type: man ls. The “man” command also has a manual, try it. Press q to quit the man command. if you havent installed man, just install it with apt-get install man.
Second, if there is no man page, the command might be a shell built-in. In that case use the “help <X>” command. E.g. help cd
Also, your favorite search-engine is your friend. Learn how to use it! I recommend DuckDuckGo.</p>
<table>
<thead>
<tr>
<th>Command</th>
<th>Synopsis</th>
<th>Description</th>
<th>Options</th>
</tr>
</thead>
<tbody>
<tr>
<td>ls</td>
<td>ls [OPTION]... [FILE]...</td>
<td>List  information  about the FILEs (the current directory by default).  Sort entries alphabetically if none of
  -cftuvSUX nor --sort is specified.</td>
<td>-a, -A, --author. -b, --block-size=SIZE</td>
</tr>
<tr>
<td>cd</td>
<td>cd [-L|[-P [-e]] [-@]] [dir]</td>
<td>Change the current directory to DIR. The default DIR is the value of the HOME shell variable.</td>
<td>-L, -P, -e, -@</td>
</tr>
<tr>
<td>cat</td>
<td>cat [OPTION]... [FILE]...</td>
<td>Concatenate files and print on the standard output.</td>
<td>-A, -b, -e, -E, -n, -s</td>
</tr>
<tr>
<td>file</td>
<td>file [-bcdEhiklLNnprsSvzZ0] [--apple] [--extension] [--mime-encoding] [--mime-type] [-e testname] [-F separator]
          [-f namefile] [-m magicfiles] [-P name=value] file ...
  file -C [-m magicfiles]
  file [--help]</td>
<td>Determine file type.</td>
<td>--apple, --extension, --mime-encoding, --mime-type, -e testname, -F separator, [-f namefile], -m magicfiles, -P name=value</td>
</tr>
<tr>
<td>du</td>
<td>du [OPTION]... [FILE]...
       du [OPTION]... --files0-from=F</td>
<td>Estimate file space usage.</td>
<td>-0, -a, -apparent-size, -B, -b</td>
</tr>
<tr>
<td>find</td>
<td>find [-H] [-L] [-P] [-D debugopts] [-Olevel] [starting-point...] [expression]</td>
<td>Search for files in a directory hierarchy</td>
<td>-H, -L, -P, -D, -Olevel, starting-point</td>
</tr>
</tbody>
</table>

<h2>Bandit Level 6</h2>
<h3>Level Goal: </h3>
<p>The password for the next level is stored somewhere on the server and has all of the following properties: </p>
<ul>
<li>owned by user bandit7</li>
<li>owned by group bandit6</li>
<li>33 bytes in size</li>
</ul>
<table>
<thead>
<tr>
<th>Host</th>
<th>Port</th>
<th>Password</th>
</tr>
</thead>
<tbody>
<tr>
<td>bandit6@bandit.labs.overthewire.org</td>
<td>2220</td>
<td>DXjZPULLxYr17uwoI01bNLQbtFemEgo7</td>
</tr>
</tbody>
</table>
<h3>Kali Commands: </h3>
<h3>Information: </h3>
<p>First, if you know a command, but don’t know how to use it, try the manual (man page) by entering “man <command>” (without the quotes). e.g. if you know about the “ls” command, type: man ls. The “man” command also has a manual, try it. Press q to quit the man command. if you havent installed man, just install it with apt-get install man.
Second, if there is no man page, the command might be a shell built-in. In that case use the “help <X>” command. E.g. help cd
Also, your favorite search-engine is your friend. Learn how to use it! I recommend DuckDuckGo.</p>
<table>
<thead>
<tr>
<th>Command</th>
<th>Synopsis</th>
<th>Description</th>
<th>Options</th>
</tr>
</thead>
<tbody>
<tr>
<td>ls</td>
<td>ls [OPTION]... [FILE]...</td>
<td>List  information  about the FILEs (the current directory by default).  Sort entries alphabetically if none of
  -cftuvSUX nor --sort is specified.</td>
<td>-a, -A, --author. -b, --block-size=SIZE</td>
</tr>
<tr>
<td>cd</td>
<td>cd [-L|[-P [-e]] [-@]] [dir]</td>
<td>Change the current directory to DIR. The default DIR is the value of the HOME shell variable.</td>
<td>-L, -P, -e, -@</td>
</tr>
<tr>
<td>cat</td>
<td>cat [OPTION]... [FILE]...</td>
<td>Concatenate files and print on the standard output.</td>
<td>-A, -b, -e, -E, -n, -s</td>
</tr>
<tr>
<td>file</td>
<td>file [-bcdEhiklLNnprsSvzZ0] [--apple] [--extension] [--mime-encoding] [--mime-type] [-e testname] [-F separator]
          [-f namefile] [-m magicfiles] [-P name=value] file ...
  file -C [-m magicfiles]
  file [--help]</td>
<td>Determine file type.</td>
<td>--apple, --extension, --mime-encoding, --mime-type, -e testname, -F separator, [-f namefile], -m magicfiles, -P name=value</td>
</tr>
<tr>
<td>du</td>
<td>du [OPTION]... [FILE]...
       du [OPTION]... --files0-from=F</td>
<td>Estimate file space usage.</td>
<td>-0, -a, -apparent-size, -B, -b</td>
</tr>
<tr>
<td>find</td>
<td>find [-H] [-L] [-P] [-D debugopts] [-Olevel] [starting-point...] [expression]</td>
<td>Search for files in a directory hierarchy</td>
<td>-H, -L, -P, -D, -Olevel, starting-point</td>
</tr>
<td>grep</td>
<td>grep [OPTION...] PATTERNS [FILE...]
       grep [OPTION...] -e PATTERNS ... [FILE...]
       grep [OPTION...] -f PATTERN_FILE ... [FILE...]</td>
<td>grep, egrep, fgrep, rgrep - print lines that match patterns/td>
<td>-E, -F, -r, --help, --version</td>
</tr>
</tbody>
</table>

<h2>Bandit Level 7</h2>
<h3>Level Goal: </h3>
<p>The password for the next level is stored in the file <strong>data.txt</strong> next to the word <strong>millionth</strong></p>
<table>
<thead>
<tr>
<th>Host</th>
<th>Port</th>
<th>Password</th>
</tr>
</thead>
<tbody>
<tr>
<td>bandit7@bandit.labs.overthewire.org</td>
<td>2220</td>
<td>HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs</td>
</tr>
</tbody>
</table>
<h3>Kali Commands: </h3>
<h3>Information: </h3>
<p>First, if you know a command, but don’t know how to use it, try the manual (man page) by entering “man <command>” (without the quotes). e.g. if you know about the “ls” command, type: man ls. The “man” command also has a manual, try it. Press q to quit the man command. if you havent installed man, just install it with apt-get install man.
Second, if there is no man page, the command might be a shell built-in. In that case use the “help <X>” command. E.g. help cd
Also, your favorite search-engine is your friend. Learn how to use it! I recommend DuckDuckGo.</p>
<table>
<thead>
<tr>
<th>Command</th>
<th>Synopsis</th>
<th>Description</th>
<th>Options</th>
</tr>
</thead>
<tbody>

<tr>
<td>grep</td>
<td>grep [OPTION...] PATTERNS [FILE...]
       grep [OPTION...] -e PATTERNS ... [FILE...]
       grep [OPTION...] -f PATTERN_FILE ... [FILE...]</td>
<td>grep, egrep, fgrep, rgrep - print lines that match patterns/td>
<td>-E, -F, -r, --help, --version</td>
</tr>

<tr>
<td>sort</td>
<td>sort [OPTION]... [FILE]...
    sort [OPTION]... --files0-from=F</td>
<td>Sort lines of text files</td>
<td>-b, -d, -f, -g, -i</td>
</tr>

<tr>
<td>uniq</td>
<td>uniq [OPTION]... [INPUT [OUTPUT]]</td>
<td>Report or omit repeated lines</td>
<td>--count, --repeated, -D, --all-repeated[=METHOD], -f</td>
</tr>

<tr>
<td>strings</td>
<td>strings [OPTIONS] FILENAME</td>
<td>grab human-readable files.</td>
<td>-n, -t, -a, -d, -s</td>
</tr>

<tr>
<td>base64</td>
<td>base64 [OPTION]... [FILE]</td>
<td>base64 encode/decode data and print to standard output</td>
<td>-d, -i, -w, --help, --version</td>
</tr>

<tr>
<td>tr</td>
<td>tr [OPTION]... SET1 [SET2]</td>
<td>translate or delete characters</td>
<td>-c, -d, -s, -t, --help, --version</td>
</tr>

<tr>
<td>tar</td>
<td>UNIX-style usage: tar -A [OPTIONS] ARCHIVE ARCHIVE
GNU-style usage: tar {--catenate|--concatenate} [OPTIONS] ARCHIVE ARCHIVE</td>
<td>An archiving utility</td>
<td>-A, -c, -d, -t, -r, -u, -x</td>
</tr>

<tr>
<td>gzip, gunzip, zcat</td>
<td> gzip [ -acdfhklLnNrtvV19 ] [-S suffix] [ name ...  ]
       gunzip [ -acfhklLnNrtvV ] [-S suffix] [ name ...  ]
       zcat [ -fhLV ] [ name ...  ]</td>
<td>compress or expand files</td>
<td>-z, -d</td>
</tr>

<tr>
<td>bzip2</td>
<td>bzip2 [Options] [filename]</td>
<td>basic utility for compress and decompress files</td>
<td>-z, -d</td>
</tr>

<tr>
<td>xxd</td>
<td> xxd -h[elp]
       xxd [options] [infile [outfile]]
       xxd -r[evert] [options] [infile [outfile]]</td>
<td>Make a hexdump or do the reverse</td>
<td>-h, -r, -a</td>
</tr>

</tbody>
</table>

<h2>Bandit Level 8</h2>
<h3>Level Goal: </h3>
<p>The password for the next level is stored in the file data.txt and is the only line of text that occurs only once</p>
<table>
<thead>
<tr>
<th>Host</th>
<th>Port</th>
<th>Password</th>
</tr>
</thead>
<tbody>
<tr>
<td>bandit8@bandit.labs.overthewire.org</td>
<td>2220</td>
<td>cvX2JJa4CFALtqS87jk27qwqGhBM9plV</td>
</tr>
</tbody>
</table>
<h3>Kali Commands: </h3>
<h3>Information: </h3>
<p>First, if you know a command, but don’t know how to use it, try the manual (man page) by entering “man <command>” (without the quotes). e.g. if you know about the “ls” command, type: man ls. The “man” command also has a manual, try it. Press q to quit the man command. if you havent installed man, just install it with apt-get install man.
Second, if there is no man page, the command might be a shell built-in. In that case use the “help <X>” command. E.g. help cd
Also, your favorite search-engine is your friend. Learn how to use it! I recommend DuckDuckGo.</p>
<table>
<thead>
<tr>
<th>Command</th>
<th>Synopsis</th>
<th>Description</th>
<th>Options</th>
</tr>
</thead>
<tbody>

<tr>
<td>grep</td>
<td>grep [OPTION...] PATTERNS [FILE...]
       grep [OPTION...] -e PATTERNS ... [FILE...]
       grep [OPTION...] -f PATTERN_FILE ... [FILE...]</td>
<td>grep, egrep, fgrep, rgrep - print lines that match patterns/td>
<td>-E, -F, -r, --help, --version</td>
</tr>

<tr>
<td>sort</td>
<td>sort [OPTION]... [FILE]...
    sort [OPTION]... --files0-from=F</td>
<td>Sort lines of text files</td>
<td>-b, -d, -f, -g, -i</td>
</tr>

<tr>
<td>uniq</td>
<td>uniq [OPTION]... [INPUT [OUTPUT]]</td>
<td>Report or omit repeated lines</td>
<td>--count, --repeated, -D, --all-repeated[=METHOD], -f</td>
</tr>

<tr>
<td>strings</td>
<td>strings [OPTIONS] FILENAME</td>
<td>grab human-readable files.</td>
<td>-n, -t, -a, -d, -s</td>
</tr>

<tr>
<td>base64</td>
<td>base64 [OPTION]... [FILE]</td>
<td>base64 encode/decode data and print to standard output</td>
<td>-d, -i, -w, --help, --version</td>
</tr>

<tr>
<td>tr</td>
<td>tr [OPTION]... SET1 [SET2]</td>
<td>translate or delete characters</td>
<td>-c, -d, -s, -t, --help, --version</td>
</tr>

<tr>
<td>tar</td>
<td>UNIX-style usage: tar -A [OPTIONS] ARCHIVE ARCHIVE
GNU-style usage: tar {--catenate|--concatenate} [OPTIONS] ARCHIVE ARCHIVE</td>
<td>An archiving utility</td>
<td>-A, -c, -d, -t, -r, -u, -x</td>
</tr>

<tr>
<td>gzip, gunzip, zcat</td>
<td> gzip [ -acdfhklLnNrtvV19 ] [-S suffix] [ name ...  ]
       gunzip [ -acfhklLnNrtvV ] [-S suffix] [ name ...  ]
       zcat [ -fhLV ] [ name ...  ]</td>
<td>compress or expand files</td>
<td>-z, -d</td>
</tr>

<tr>
<td>bzip2</td>
<td>bzip2 [Options] [filename]</td>
<td>basic utility for compress and decompress files</td>
<td>-z, -d</td>
</tr>

<tr>
<td>xxd</td>
<td> xxd -h[elp]
       xxd [options] [infile [outfile]]
       xxd -r[evert] [options] [infile [outfile]]</td>
<td>Make a hexdump or do the reverse</td>
<td>-h, -r, -a</td>
</tr>

</tbody>
</table>
<h3>Helpful Reading Material</h3>
<p><a href="https://ryanstutorials.net/linuxtutorial/piping.php" target="_blank">Piping and Redirection</a></p>


<h2>Bandit Level 9</h2>
<h3>Level Goal: </h3>
<p>The password for the next level is stored in the file data.txt in one of the few human-readable strings, preceded by several ‘=’ characters.</p>
<table>
<thead>
<tr>
<th>Host</th>
<th>Port</th>
<th>Password</th>
</tr>
</thead>
<tbody>
<tr>
<td>bandit9@bandit.labs.overthewire.org</td>
<td>2220</td>
<td>UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR</td>
</tr>
</tbody>
</table>
<h3>Kali Commands: </h3>
<h3>Information: </h3>
<p>First, if you know a command, but don’t know how to use it, try the manual (man page) by entering “man <command>” (without the quotes). e.g. if you know about the “ls” command, type: man ls. The “man” command also has a manual, try it. Press q to quit the man command. if you havent installed man, just install it with apt-get install man.
Second, if there is no man page, the command might be a shell built-in. In that case use the “help <X>” command. E.g. help cd
Also, your favorite search-engine is your friend. Learn how to use it! I recommend DuckDuckGo.</p>
<table>
<thead>
<tr>
<th>Command</th>
<th>Synopsis</th>
<th>Description</th>
<th>Options</th>
</tr>
</thead>
<tbody>

<tr>
<td>grep</td>
<td>grep [OPTION...] PATTERNS [FILE...]
       grep [OPTION...] -e PATTERNS ... [FILE...]
       grep [OPTION...] -f PATTERN_FILE ... [FILE...]</td>
<td>grep, egrep, fgrep, rgrep - print lines that match patterns/td>
<td>-E, -F, -r, --help, --version</td>
</tr>

<tr>
<td>sort</td>
<td>sort [OPTION]... [FILE]...
    sort [OPTION]... --files0-from=F</td>
<td>Sort lines of text files</td>
<td>-b, -d, -f, -g, -i</td>
</tr>

<tr>
<td>uniq</td>
<td>uniq [OPTION]... [INPUT [OUTPUT]]</td>
<td>Report or omit repeated lines</td>
<td>--count, --repeated, -D, --all-repeated[=METHOD], -f</td>
</tr>

<tr>
<td>strings</td>
<td>strings [OPTIONS] FILENAME</td>
<td>grab human-readable files.</td>
<td>-n, -t, -a, -d, -s</td>
</tr>

<tr>
<td>base64</td>
<td>base64 [OPTION]... [FILE]</td>
<td>base64 encode/decode data and print to standard output</td>
<td>-d, -i, -w, --help, --version</td>
</tr>

<tr>
<td>tr</td>
<td>tr [OPTION]... SET1 [SET2]</td>
<td>translate or delete characters</td>
<td>-c, -d, -s, -t, --help, --version</td>
</tr>

<tr>
<td>tar</td>
<td>UNIX-style usage: tar -A [OPTIONS] ARCHIVE ARCHIVE
GNU-style usage: tar {--catenate|--concatenate} [OPTIONS] ARCHIVE ARCHIVE</td>
<td>An archiving utility</td>
<td>-A, -c, -d, -t, -r, -u, -x</td>
</tr>

<tr>
<td>gzip, gunzip, zcat</td>
<td> gzip [ -acdfhklLnNrtvV19 ] [-S suffix] [ name ...  ]
       gunzip [ -acfhklLnNrtvV ] [-S suffix] [ name ...  ]
       zcat [ -fhLV ] [ name ...  ]</td>
<td>compress or expand files</td>
<td>-z, -d</td>
</tr>

<tr>
<td>bzip2</td>
<td>bzip2 [Options] [filename]</td>
<td>basic utility for compress and decompress files</td>
<td>-z, -d</td>
</tr>

<tr>
<td>xxd</td>
<td> xxd -h[elp]
       xxd [options] [infile [outfile]]
       xxd -r[evert] [options] [infile [outfile]]</td>
<td>Make a hexdump or do the reverse</td>
<td>-h, -r, -a</td>
</tr>

</tbody>
</table>

<h2>Bandit Level 8</h2>
<h3>Level Goal: </h3>
<p>The password for the next level is stored in the file data.txt and is the only line of text that occurs only once</p>
<table>
<thead>
<tr>
<th>Host</th>
<th>Port</th>
<th>Password</th>
</tr>
</thead>
<tbody>
<tr>
<td>bandit8@bandit.labs.overthewire.org</td>
<td>2220</td>
<td>cvX2JJa4CFALtqS87jk27qwqGhBM9plV</td>
</tr>
</tbody>
</table>
<h3>Kali Commands: </h3>
<h3>Information: </h3>
<p>First, if you know a command, but don’t know how to use it, try the manual (man page) by entering “man <command>” (without the quotes). e.g. if you know about the “ls” command, type: man ls. The “man” command also has a manual, try it. Press q to quit the man command. if you havent installed man, just install it with apt-get install man.
Second, if there is no man page, the command might be a shell built-in. In that case use the “help <X>” command. E.g. help cd
Also, your favorite search-engine is your friend. Learn how to use it! I recommend DuckDuckGo.</p>
<table>
<thead>
<tr>
<th>Command</th>
<th>Synopsis</th>
<th>Description</th>
<th>Options</th>
</tr>
</thead>
<tbody>

<tr>
<td>grep</td>
<td>grep [OPTION...] PATTERNS [FILE...]
       grep [OPTION...] -e PATTERNS ... [FILE...]
       grep [OPTION...] -f PATTERN_FILE ... [FILE...]</td>
<td>grep, egrep, fgrep, rgrep - print lines that match patterns/td>
<td>-E, -F, -r, --help, --version</td>
</tr>

<tr>
<td>sort</td>
<td>sort [OPTION]... [FILE]...
    sort [OPTION]... --files0-from=F</td>
<td>Sort lines of text files</td>
<td>-b, -d, -f, -g, -i</td>
</tr>

<tr>
<td>uniq</td>
<td>uniq [OPTION]... [INPUT [OUTPUT]]</td>
<td>Report or omit repeated lines</td>
<td>--count, --repeated, -D, --all-repeated[=METHOD], -f</td>
</tr>

<tr>
<td>strings</td>
<td>strings [OPTIONS] FILENAME</td>
<td>grab human-readable files.</td>
<td>-n, -t, -a, -d, -s</td>
</tr>

<tr>
<td>base64</td>
<td>base64 [OPTION]... [FILE]</td>
<td>base64 encode/decode data and print to standard output</td>
<td>-d, -i, -w, --help, --version</td>
</tr>

<tr>
<td>tr</td>
<td>tr [OPTION]... SET1 [SET2]</td>
<td>translate or delete characters</td>
<td>-c, -d, -s, -t, --help, --version</td>
</tr>

<tr>
<td>tar</td>
<td>UNIX-style usage: tar -A [OPTIONS] ARCHIVE ARCHIVE
GNU-style usage: tar {--catenate|--concatenate} [OPTIONS] ARCHIVE ARCHIVE</td>
<td>An archiving utility</td>
<td>-A, -c, -d, -t, -r, -u, -x</td>
</tr>

<tr>
<td>gzip, gunzip, zcat</td>
<td> gzip [ -acdfhklLnNrtvV19 ] [-S suffix] [ name ...  ]
       gunzip [ -acfhklLnNrtvV ] [-S suffix] [ name ...  ]
       zcat [ -fhLV ] [ name ...  ]</td>
<td>compress or expand files</td>
<td>-z, -d</td>
</tr>

<tr>
<td>bzip2</td>
<td>bzip2 [Options] [filename]</td>
<td>basic utility for compress and decompress files</td>
<td>-z, -d</td>
</tr>

<tr>
<td>xxd</td>
<td> xxd -h[elp]
       xxd [options] [infile [outfile]]
       xxd -r[evert] [options] [infile [outfile]]</td>
<td>Make a hexdump or do the reverse</td>
<td>-h, -r, -a</td>
</tr>

</tbody>
</table>


<h2>Bandit Level 9</h2>
<h3>Level Goal: </h3>
<p>The password for the next level is stored in the file data.txt in one of the few human-readable strings, preceded by several ‘=’ characters.</p>
<table>
<thead>
<tr>
<th>Host</th>
<th>Port</th>
<th>Password</th>
</tr>
</thead>
<tbody>
<tr>
<td>bandit9@bandit.labs.overthewire.org</td>
<td>2220</td>
<td>UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR</td>
</tr>
</tbody>
</table>
<h3>Kali Commands: </h3>
<h3>Information: </h3>
<p>First, if you know a command, but don’t know how to use it, try the manual (man page) by entering “man <command>” (without the quotes). e.g. if you know about the “ls” command, type: man ls. The “man” command also has a manual, try it. Press q to quit the man command. if you havent installed man, just install it with apt-get install man.
Second, if there is no man page, the command might be a shell built-in. In that case use the “help <X>” command. E.g. help cd
Also, your favorite search-engine is your friend. Learn how to use it! I recommend DuckDuckGo.</p>
<table>
<thead>
<tr>
<th>Command</th>
<th>Synopsis</th>
<th>Description</th>
<th>Options</th>
</tr>
</thead>
<tbody>

<tr>
<td>grep</td>
<td>grep [OPTION...] PATTERNS [FILE...]
       grep [OPTION...] -e PATTERNS ... [FILE...]
       grep [OPTION...] -f PATTERN_FILE ... [FILE...]</td>
<td>grep, egrep, fgrep, rgrep - print lines that match patterns/td>
<td>-E, -F, -r, --help, --version</td>
</tr>

<tr>
<td>sort</td>
<td>sort [OPTION]... [FILE]...
    sort [OPTION]... --files0-from=F</td>
<td>Sort lines of text files</td>
<td>-b, -d, -f, -g, -i</td>
</tr>

<tr>
<td>uniq</td>
<td>uniq [OPTION]... [INPUT [OUTPUT]]</td>
<td>Report or omit repeated lines</td>
<td>--count, --repeated, -D, --all-repeated[=METHOD], -f</td>
</tr>

<tr>
<td>strings</td>
<td>strings [OPTIONS] FILENAME</td>
<td>grab human-readable files.</td>
<td>-n, -t, -a, -d, -s</td>
</tr>

<tr>
<td>base64</td>
<td>base64 [OPTION]... [FILE]</td>
<td>base64 encode/decode data and print to standard output</td>
<td>-d, -i, -w, --help, --version</td>
</tr>

<tr>
<td>tr</td>
<td>tr [OPTION]... SET1 [SET2]</td>
<td>translate or delete characters</td>
<td>-c, -d, -s, -t, --help, --version</td>
</tr>

<tr>
<td>tar</td>
<td>UNIX-style usage: tar -A [OPTIONS] ARCHIVE ARCHIVE
GNU-style usage: tar {--catenate|--concatenate} [OPTIONS] ARCHIVE ARCHIVE</td>
<td>An archiving utility</td>
<td>-A, -c, -d, -t, -r, -u, -x</td>
</tr>

<tr>
<td>gzip, gunzip, zcat</td>
<td> gzip [ -acdfhklLnNrtvV19 ] [-S suffix] [ name ...  ]
       gunzip [ -acfhklLnNrtvV ] [-S suffix] [ name ...  ]
       zcat [ -fhLV ] [ name ...  ]</td>
<td>compress or expand files</td>
<td>-z, -d</td>
</tr>

<tr>
<td>bzip2</td>
<td>bzip2 [Options] [filename]</td>
<td>basic utility for compress and decompress files</td>
<td>-z, -d</td>
</tr>

<tr>
<td>xxd</td>
<td> xxd -h[elp]
       xxd [options] [infile [outfile]]
       xxd -r[evert] [options] [infile [outfile]]</td>
<td>Make a hexdump or do the reverse</td>
<td>-h, -r, -a</td>
</tr>

</tbody>
</table>

<h2>Bandit Level 10</h2>
<h3>Level Goal: </h3>
<p>The password for the next level is stored in the file data.txt, which contains base64 encoded data</p>
<table>
<thead>
<tr>
<th>Host</th>
<th>Port</th>
<th>Password</th>
</tr>
</thead>
<tbody>
<tr>
<td>bandit10@bandit.labs.overthewire.org</td>
<td>2220</td>
<td>cvX2JJa4CFALtqS87jk27qwqGhBM9plV</td>
</tr>
</tbody>
</table>
<h3>Kali Commands: </h3>
<h3>Information: </h3>
<p>First, if you know a command, but don’t know how to use it, try the manual (man page) by entering “man <command>” (without the quotes). e.g. if you know about the “ls” command, type: man ls. The “man” command also has a manual, try it. Press q to quit the man command. if you havent installed man, just install it with apt-get install man.
Second, if there is no man page, the command might be a shell built-in. In that case use the “help <X>” command. E.g. help cd
Also, your favorite search-engine is your friend. Learn how to use it! I recommend DuckDuckGo.</p>
<table>
<thead>
<tr>
<th>Command</th>
<th>Synopsis</th>
<th>Description</th>
<th>Options</th>
</tr>
</thead>
<tbody>

<tr>
<td>grep</td>
<td>grep [OPTION...] PATTERNS [FILE...]
       grep [OPTION...] -e PATTERNS ... [FILE...]
       grep [OPTION...] -f PATTERN_FILE ... [FILE...]</td>
<td>grep, egrep, fgrep, rgrep - print lines that match patterns/td>
<td>-E, -F, -r, --help, --version</td>
</tr>

<tr>
<td>sort</td>
<td>sort [OPTION]... [FILE]...
    sort [OPTION]... --files0-from=F</td>
<td>Sort lines of text files</td>
<td>-b, -d, -f, -g, -i</td>
</tr>

<tr>
<td>uniq</td>
<td>uniq [OPTION]... [INPUT [OUTPUT]]</td>
<td>Report or omit repeated lines</td>
<td>--count, --repeated, -D, --all-repeated[=METHOD], -f</td>
</tr>

<tr>
<td>strings</td>
<td>strings [OPTIONS] FILENAME</td>
<td>grab human-readable files.</td>
<td>-n, -t, -a, -d, -s</td>
</tr>

<tr>
<td>base64</td>
<td>base64 [OPTION]... [FILE]</td>
<td>base64 encode/decode data and print to standard output</td>
<td>-d, -i, -w, --help, --version</td>
</tr>

<tr>
<td>tr</td>
<td>tr [OPTION]... SET1 [SET2]</td>
<td>translate or delete characters</td>
<td>-c, -d, -s, -t, --help, --version</td>
</tr>

<tr>
<td>tar</td>
<td>UNIX-style usage: tar -A [OPTIONS] ARCHIVE ARCHIVE
GNU-style usage: tar {--catenate|--concatenate} [OPTIONS] ARCHIVE ARCHIVE</td>
<td>An archiving utility</td>
<td>-A, -c, -d, -t, -r, -u, -x</td>
</tr>

<tr>
<td>gzip, gunzip, zcat</td>
<td> gzip [ -acdfhklLnNrtvV19 ] [-S suffix] [ name ...  ]
       gunzip [ -acfhklLnNrtvV ] [-S suffix] [ name ...  ]
       zcat [ -fhLV ] [ name ...  ]</td>
<td>compress or expand files</td>
<td>-z, -d</td>
</tr>

<tr>
<td>bzip2</td>
<td>bzip2 [Options] [filename]</td>
<td>basic utility for compress and decompress files</td>
<td>-z, -d</td>
</tr>

<tr>
<td>xxd</td>
<td> xxd -h[elp]
       xxd [options] [infile [outfile]]
       xxd -r[evert] [options] [infile [outfile]]</td>
<td>Make a hexdump or do the reverse</td>
<td>-h, -r, -a</td>
</tr>

</tbody>
</table>
<h3></h3>
<p><a href="https://en.wikipedia.org/wiki/Base64" target="_blank">Base64 on Wikipedia</p>