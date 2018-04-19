# imapsync
imapsync - Email IMAP tool for syncing, copying and migrating email mailboxes between two imap servers, one way, and without duplicates.

#### Usage:

 To synchronize the source imap account
       "test1" on server "test1.lamiral.info" with password "secret1"
     to the destination imap account
       "test2" on server "test2.lamiral.info" with password "secret2"
do:

     docker run basivireddy/imapsync imapsync \
       --host1 test1.lamiral.info --user1 test1 --password1 secret1 \
       --host2 test2.lamiral.info --user2 test2 --password2 secret2
