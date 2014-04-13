{\rtf1\ansi\ansicpg1252\cocoartf1265\cocoasubrtf190
{\fonttbl\f0\fnil\fcharset0 Cambria;\f1\ftech\fcharset77 Symbol;\f2\froman\fcharset0 TimesNewRomanPSMT;
}
{\colortbl;\red255\green255\blue255;\red0\green0\blue255;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid1\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid1}
{\list\listtemplateid2\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid101\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid2}
{\list\listtemplateid3\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid201\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid3}
{\list\listtemplateid4\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid301\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid4}
{\list\listtemplateid5\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid401\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid5}
{\list\listtemplateid6\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid501\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid6}
{\list\listtemplateid7\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid601\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid7}
{\list\listtemplateid8\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid701\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid8}
{\list\listtemplateid9\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid801\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid9}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}{\listoverride\listid2\listoverridecount0\ls2}{\listoverride\listid3\listoverridecount0\ls3}{\listoverride\listid4\listoverridecount0\ls4}{\listoverride\listid5\listoverridecount0\ls5}{\listoverride\listid6\listoverridecount0\ls6}{\listoverride\listid7\listoverridecount0\ls7}{\listoverride\listid8\listoverridecount0\ls8}{\listoverride\listid9\listoverridecount0\ls9}}
\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\ri720

\f0\b\fs24 \cf0 MIGIT\
\
Documentation\
\
Commands
\b0 \
\
GIT MIGIT\
\
GIT MIGIT HELP\
\pard\pardeftab720\li720\fi-360\ri720
\ls1\ilvl0
\f1 \cf0 \'a5	
\f0 Provides a list of options and arguments that GIT MIGIT supports with a brief description\
\pard\pardeftab720\ri720
\cf0 GIT MIGIT SHOW [FILE]\
\pard\pardeftab720\li720\fi-360\ri720
\ls2\ilvl0
\f1 \cf0 \'a5	
\f0 Shows all the migration commits and the contents of the file for each of these commits\
\ls2\ilvl0
\f1 \'a5	
\f0 git migit show example.sql\
\pard\pardeftab720\ri720
\cf0 GIT MIGIT SHOW [FILE] [HASH]\
\pard\pardeftab720\li720\fi-360\ri720
\ls3\ilvl0
\f1 \cf0 \'a5	
\f0 Shows the contents of the file for the commit hash\
\ls3\ilvl0
\f1 \'a5	
\f0 git migit show example.sql s3g8d\
\pard\pardeftab720\ri720
\cf0 GIT MIGIT SHOW [FILE] [HASH-from] [HASH-to]\
\pard\pardeftab720\li720\fi-360\ri720
\ls4\ilvl0
\f1 \cf0 \'a5	
\f0 Shows all the migration commits and contents of the file between the two given commit hashes\
\ls4\ilvl0
\f1 \'a5	
\f0 git migit show example.sql s3g8d 487fe\
\pard\pardeftab720\ri720
\cf0 GIT MIGIT SHOW [FILE] [\'96BEFORE/-AFTER] [HASH]\
\pard\pardeftab720\li720\fi-360\ri720
\ls5\ilvl0
\f1 \cf0 \'a5	
\f0 Shows all the contents of a file before or after a given commit hash\
\ls5\ilvl0
\f1 \'a5	
\f0 git migit show example.sql \'96before 487fe\
\ls5\ilvl0
\f1 \'a5	
\f0 git migit show example.sql \'96after 487fe\
\pard\pardeftab720\ri720
\cf0 GIT MIGIT STATUS\
\pard\pardeftab720\li720\fi-360\ri720
\ls6\ilvl0
\f1 \cf0 \'a5	
\f0 Shows the Migration folder Path and its contents\
\pard\pardeftab720\ri720
\cf0 GIT MIGIT LOG\
\pard\pardeftab720\li720\fi-360\ri720
\ls7\ilvl0
\f1 \cf0 \'a5	
\f0 Shows all migration commits\
\ls7\ilvl0
\f1 \'a5	
\f0 This commands supports all the arguments that git log supports\
\ls7\ilvl0
\f1 \'a5	
\f0 See here, \cf2 \ul \ulc2 https://www.kernel.org/pub/software/scm/git/docs/git-log.html
\f2 \cf0 \ulnone \
\pard\pardeftab720\ri720
\cf0 \
\pard\pardeftab720\ri720

\f0 \cf0 GIT MIGIT-INIT\
\pard\pardeftab720\li720\fi-360\ri720
\ls8\ilvl0
\f1 \cf0 \'a5	
\f0 After installing MIGIT, use this command to set up the environment\
\ls8\ilvl0
\f1 \'a5	
\f0 Follow the on-screen instructions\
\ls8\ilvl0
\f1 \'a5	
\f0 This will create a migration directory and add the required hooks to the .git/hooks directory\
\pard\pardeftab720\ri720

\f2 \cf0 \
\pard\pardeftab720\ri720

\f0 \cf0 GIT CONFIGURE-PATH\
\pard\pardeftab720\li720\fi-360\ri720
\ls9\ilvl0
\f1 \cf0 \'a5	
\f0 Once MIGIT has been set in your GIT repository, this command gives you the ability to change the MIGRATION directory.  \
\ls9\ilvl0
\f1 \'a5	
\f0 WARNING: if you change the directory, to see the previously committed Migrations, it requires the path of the previous MIGRATION directory \
}