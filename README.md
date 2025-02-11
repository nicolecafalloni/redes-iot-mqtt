  **Passos para rodar os arquivos**

1. **Verificar os requisitos**  
   - Abra os arquivos e veja se há importação de bibliotecas externas.  
   - Se houver, instale as dependências antes de executar os scripts.  

2. **Iniciar o Subscriber primeiro**  
   - Esse arquivo é responsável por receber as mensagens.  
   - Ele deve ser executado primeiro para garantir que esteja pronto para receber dados.  

3. **Rodar o Publisher**  
   - Esse arquivo é responsável por enviar mensagens.  
   - Depois que o subscriber estiver rodando, execute o publisher para começar a comunicação.  

4. **Testar a comunicação**  
   - Verifique se as mensagens enviadas pelo publisher estão aparecendo no subscriber.  
   - Caso contrário, confira se os dois estão configurados corretamente para se comunicar.  

5. **Corrigir possíveis erros**  
   - Se houver falha na comunicação, verifique conexões, portas e dependências.  
   - Veja se ambos os scripts estão apontando para o mesmo servidor ou broker, caso usem um.
