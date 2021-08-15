# languagetool
lanagetool self hosted

steps needed for this language tool to work

you can install this docker one of two ways 

1 using docker compose. 
Please see the the yaml file and modify to suit your needs

2 using docker run command 
docker run --rm -it -p 8010:8010 -e langtool_languageModel=/ngrams -v home/john/ngrams:/ngrams erikvl87/languagetool

modify this run command to meed your needs and enviroment
