# setting_zsh-git-prompt

using this repository.

https://github.com/olivierverdier/zsh-git-prompt

## set
execute the following commands.
<pre>
chsh -s /bin/zsh
brew install zsh-git-prompt
vi ~/.zshrc
</pre>
add the following into .zshrc file.
<pre><code>
source "/usr/local/opt/zsh-git-prompt/zshrc.sh"
PROMPT='%10F%B%n@%m%b%f:%12F%B%c%b%f%f$(git_super_status) %# '
</code></pre>

## reflect
execute the following command.
<pre>
source ~/.zshrc
</pre>
