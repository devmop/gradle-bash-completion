gradle-bash-completion
======================

Bash completion for gradle


Copy gradle into /etc/bash_completion.d/  
Copy completion.gradle into /etc/gradle/


Inspired by https://gist.github.com/nolanlawson/8694399 and http://www.practicalgradle.org/blog/2011/02/task-auto-completion-on-the-command-line/

The results currently aren't cached as completion then won't function as expected with gradle builds that import ant ones.

As a result it feels slow even with the gradle daemon running.
