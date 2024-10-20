# fp-pc-console-future-additions

After finishing the 2024 backups, I realized I would like to add a couple small things to the guides:

Install rsync

And also I created a home directory backup something like this
~~~
tar -zcvpf /backup/akash-backup-$(date +%d-%m-%Y).tar.gz /home/akash
~~~
I think that keeps permissions in tact, but can't be opened up on a basic exFat partition, so just be sure to do your installation on somethiing like an ext4 partition, and then copy this home directory backup to the home folder, and open it up there and overwrite the home dir contents.


