.zshrc
======

My personal modification to the [robbyrussel](https://github.com/robbyrussell/oh-my-zsh) theme for the zsh terminal.

An example 

![simple sample](/screen-samples/simple-sample.jpg)

And with a <code>git</code> repository

![git sample](/screen-samples/git-sample.jpg)

Configuration
-------------

I'm using the zsh terminal, customized with [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh). I recommend you to install it with

	curl -L https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh | sh
	
and then set it as your default shell if you want with

	chsh -s /bin/zsh
	

I'm also using the [Solarized](http://ethanschoonover.com/solarized) theme, wich I've saved a copy in this repo, with font <code>Consolata</code> 15pt.
Just import it to the terminal and set it as default if wanted.

Besides, I'm using my personal modification to the robbyrussel theme, given in the <code>farolfo.zsh-theme</code> file, just copy it into your <code>~/.oh-my-zsh/themes</code> directory, and modify your <code>.zshrc</code> file so it will use this theme, by modifing the line:

	ZSH_THEME="farolfo"

Or you may copy the <code>.zshrc</code> file that I provied to your home directory.

###Further reading

A very simple and instructive tutorial

>http://net.tutsplus.com/tutorials/tools-and-tips/how-to-customize-your-command-prompt/
