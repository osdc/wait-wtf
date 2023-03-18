# The Terminal opens in vim:
> Edited ~/.bashrc and remove last line saying `vim`

# I can't access the internet?
> Restarted NetworkManager systemd service using `sudo systemctl restart NetworkManager`

# wait, wtf happened to sudo?
> `sudo` has been renamed to `wtf`. So, went into su shell by `wtf su` then renamed `wtf` to `sudo` by
> `mv /usr/bin/wtf /usr/bin/sudo`

# Shut it, Firefox.
> Removed last line from cron by using `crontab -e`

# End-Sem Project
> 1. First installed *gcc git g++ make* by `sudo apt install gcc git make g++`
> 2. Cloned repo by `git clone https://github.com/ecitflynn/cool-repo.git`
> `cd cool-repo`
> 3. Tried compiling binS.c, identified error in line 13 and added trailing `;`
> 4. Installed emojicode compiler from `https://www.emojicode.org/docs/guides/` by running 
> `wget https://github.com/emojicode/emojicode/releases/download/v1.0-beta.2/Emojicode-1.0-beta.2-Linux-x86_64.tar.gz -O emojicode.tar.gz \
> && tar -xzf emojicode.tar.gz && rm emojicode.tar.gz \
> && cd Emojicode-1.0-beta.2-Linux-x86_64 && ./install.sh \
> && cd .. && rm -r Emojicode-1.0-beta.2-Linux-x86_64`
> 5. Tried compiling, installed libncurses5 to fix missing libtinfo.so.5 error
> Added missing 🔤 in hiworld.emojic
> Successfully compiled

# Giddy-Up
> `cd ~/Downloads`
> `unzip WTFisGiT.zip && cd WTFisGiT`
> `git restore .`
