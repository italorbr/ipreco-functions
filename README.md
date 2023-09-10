# firebase function gerador de thumbnail

pra alterar o tamanho da imagem a ser gerada alterar linha 38 por ex: de "200x200>", para "250x250>",

# tem que instalar uma porrada de coisa pra funcionar e eu n tenho ctz se lembro todas 

npm install firebase
npm install firebase-functions
npm install child-process-promise

# tem que fazer login no firebase tbm antes de subir a function pro seu fb 

firebase login 

# pra subir a function

firebase deploy --only functions