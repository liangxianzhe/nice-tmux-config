# What's tmux

Tmux is a terminal multiplexer. http://tmux.sourceforge.net/

1. Easy to split screen and create windows in one terminal. Easy to copy and paste.

2. Especially nice when using ssh. No need for multiple ssh connection.

This config is to make it easy to use.

# Installation

    sudo apt-get install tmux
    git clone git@github.com:liangxianzhe/nice-tmux-config.git
    ln -s ~/nice-tmux-config/tmux.conf ~/.tmux.conf

# Usage

Run "tmux" to start a new session, or "tmux attach" to attach to a exist session.

Leader = `

First press `, then use following command:

1. For Pane

" = split pane horizontally

% = split pane vertically

x = kill the current pane

arrows or hjkl = move to panes

Ctrl + arrows = adjust pane size

q = show pane indexes

q + <index> = go to the pane with index

2. For Window

c = create a new window

& = close current window

n = go to next window

p = go to previous window

` = go the last used window! 

<index> = go the the window with index

w = show all windows

, = name current window

3. For session (added later)

d = dettach

s = show all sessions

4. For general
? = show all command

[ = enter into copy mode:

    move using hjkl,

    start select using <space>,

    copy selected area using <enter>,

    exit copy mode using q
