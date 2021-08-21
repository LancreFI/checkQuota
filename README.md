# checkQuota</br>
A shell script to automatically check your Elisa consumer mailbox quota through wm</br>
</br>
Just add your addresses to mailadds file in the format of one per row:</br>
email@some.com:password</br>
emai2@some.other.net:password</br>
</br>
Then set the settings to quoKek.sh:</br>
##THRESHOLD OF WHEN TO NOTIFY ABOUT BOX GETTING FULL</br>
THRESH=90</br>
</br>
##SETTINGS FOR THE OUTGOING MAIL</br>
SENDERNAME="POLLER"</br>
SENDERADD="poller@pollerdomain.com"</br>
RECIPIENT="someone@yourdomain.net"</br>
</br>
Run or cron.
