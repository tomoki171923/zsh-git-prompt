# setting_zsh-git-prompt

using this repository
https://github.com/olivierverdier/zsh-git-prompt

## set
<pre><code>
% chsh -s /bin/zsh
% brew install zsh-git-prompt
% vi ~/.zshrc
</code></pre>
add the following into .zshrc
<pre><code>
source "/usr/local/opt/zsh-git-prompt/zshrc.sh"
PROMPT='%10F%B%n@%m%b%f:%12F%B%c%b%f%f$(git_super_status) %# '
</code></pre>

## reflect
<pre><code>
% source ~/.zshrc
</code></pre>
