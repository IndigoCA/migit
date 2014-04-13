MIGIT
Documentation

Commands

GIT MIGIT

GIT MIGIT HELP
Provides a list of options and arguments that GIT MIGIT supports with a brief description\

GIT MIGIT SHOW [FILE]
Shows all the migration commits and the contents of the file for each of these commits\
git migit show example.sql s3g8d

GIT MIGIT SHOW [FILE] [HASH]
Shows the contents of the file for the commit hash
git migit show example.sql s3g8d

GIT MIGIT SHOW [FILE] [HASH-from] [HASH-to]
Shows all the migration commits and contents of the file between the two given commit hashes\
git migit show example.sql s3g8d 487fe

GIT MIGIT SHOW [FILE] [BEFORE/-AFTER] [HASH]
Shows all the contents of a file before or after a given commit hash
git migit show example.sql before 487fe
git migit show example.sql after 487fe

GIT MIGIT STATUS
Shows the Migration folder Path and its contents

GIT MIGIT LOG
Shows all migration commits
This commands supports all the arguments that git log supports
See here for the options https://www.kernel.org/pub/software/scm/git/docs/git-log.html

GIT MIGIT-INIT
Initializes your git enviornment to use migit, make sure you are in your git repository before you do this
After installing MIGIT, use this command to set up the environment
Follow the on-screen instructions
This will create a migration directory and add the required hooks to the .git/hooks directory

GIT CONFIGURE-PATH\
Once MIGIT has been set in your GIT repository, this command gives you the ability to change the MIGRATION directory.  
WARNING: if you change the directory, to see the previously committed Migrations, it requires the path of the previous MIGRATION directory
