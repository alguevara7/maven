for jar:

mvn install:install-file -Dfile=./evernote-api-1.21.jar -DgroupId=evernote -DartifactId=evernote-api -Dversion=1.21 -Dpackaging=jar -DcreateChecksum=true

for sources:

mvn install:install-file -Dfile=./evernote-src.jar -DgroupId=evernote -DartifactId=evernote-api -Dversion=1.21 -Dpackaging=jar -DcreateChecksum=true -Dclassifier=sources

