# CP03-Microservice
Repositório destinado ao Checkpoint 03 de Microservice

# 1.1 - Explorando Imagens

Baixe a imagem oficial do Python: <br>
<img width="1115" height="620" alt="image" src="https://github.com/user-attachments/assets/8aa0dc35-d01f-4a44-bf73-5f5e940a2447" />
<p></p>
Inspecione a imagem: <br>
<img width="867" height="489" alt="image" src="https://github.com/user-attachments/assets/1691a401-99bf-47d3-8eaa-d5b957e2e407" />

Verifique o histórico de camadas:<br>
<img width="1020" height="256" alt="image" src="https://github.com/user-attachments/assets/69c741d7-667d-4167-9095-747a29f4ae10" />

# 1.2 - Gerenciando Imagens

Baixe diferentes versões do Node.js:
 <br>
<img width="1062" height="420" alt="image" src="https://github.com/user-attachments/assets/9f9d52b4-a40c-4213-aec1-7852a4140a25" />
<img width="683" height="356" alt="image" src="https://github.com/user-attachments/assets/82df041b-8f45-43e2-8f97-75fdb9074227" />

Compare os tamanhos das imagens:  <br>
<img width="581" height="102" alt="image" src="https://github.com/user-attachments/assets/6ce0ebba-2c9d-4ac2-a99c-cf385d1f4e31" />

 Crie uma tag personalizada:  <br>
<img width="699" height="46" alt="image" src="https://github.com/user-attachments/assets/83d71107-8c3d-4b2a-b94c-c34a7a46b68e" />

 Remova imagens não utilizadas:  <br>
<img width="674" height="118" alt="image" src="https://github.com/user-attachments/assets/c21c14cb-1d4a-4597-be2c-e6185dfb183a" />

# 2.1 - primeira aplicação

Crie um diretório: <br>
<img width="652" height="249" alt="image" src="https://github.com/user-attachments/assets/4e53e31a-fb04-45ca-889c-822636896666" />

Crie um arquivo app.py:  <br>
<img width="842" height="258" alt="image" src="https://github.com/user-attachments/assets/e65206f2-1208-4cb6-b663-d3a3c259f502" />

 Crie um arquivo requirements.txt:
 <img width="692" height="149" alt="image" src="https://github.com/user-attachments/assets/3e2d487f-d586-4cfe-a000-0a3f357f2fa1" />

Criando Dockerfile:  <br>
<img width="637" height="217" alt="image" src="https://github.com/user-attachments/assets/119dccb1-bc80-4f30-b90f-089941d64b28" />

# 2.3 Build e execução:

Construa a imagem:  <br>
<img width="438" height="41" alt="image" src="https://github.com/user-attachments/assets/c88304c7-d716-4370-9712-0bf6e11469c4" />

Verifique a imagem criada:  <br>
<img width="503" height="44" alt="image" src="https://github.com/user-attachments/assets/d92e01c0-ff91-480d-84eb-e5081c362df7" />

 Execute o container:  <br>
 <img width="704" height="43" alt="image" src="https://github.com/user-attachments/assets/b1686714-eabf-471e-a4ed-fc059c670a6c" />

Teste no navegador:  <br>
<img width="329" height="133" alt="image" src="https://github.com/user-attachments/assets/44e7713f-3454-4f0e-bdda-8687d1da0789" />

Verifique os logs:  <br>
<img width="923" height="186" alt="image" src="https://github.com/user-attachments/assets/3dee4c67-59d0-408d-a52b-2be6067154c3" />

# 2.4 Otimizando o Dockerfile 
<img width="679" height="563" alt="image" src="https://github.com/user-attachments/assets/21e639d7-0c2b-40ff-9e24-b682f85f65a6" />

# 3.1 Named Volumes

Crie um volume:  <br>
<img width="465" height="142" alt="image" src="https://github.com/user-attachments/assets/fb4ce2eb-9e41-43a9-b3e9-de52d14a7b19" />

 Liste volumes:  <br>
 <img width="525" height="93" alt="image" src="https://github.com/user-attachments/assets/e9497d62-9d91-4c2d-aa21-1c4f849973bb" />

Inspecione o volume:  <br>
<img width="523" height="210" alt="image" src="https://github.com/user-attachments/assets/2239ef03-4445-46fb-b87a-c9d2648e2ce3" />

Execute PostgreSQL com volume:  <br>
<img width="1340" height="62" alt="image" src="https://github.com/user-attachments/assets/587b142f-6c1e-4e58-bbf5-1d9cdc874e6c" />

Conecte e crie uma tabela de teste:  <br>
<img width="742" height="100" alt="image" src="https://github.com/user-attachments/assets/5b6a496c-e8f1-4a4f-b7a9-980726da27d0" />

# 3.2 - Testando Persistência

Acesse o container:  <br>
<img width="582" height="46" alt="image" src="https://github.com/user-attachments/assets/8ab48b29-1f7e-4e9f-aaae-067cab9a32c4" />

Crie um banco de dados e tabela:  <br>
<img width="1090" height="344" alt="image" src="https://github.com/user-attachments/assets/86d7fd22-acd0-40a5-a12a-e567c1aa2d0a" />

Pare e remova o container:  <br>
<img width="637" height="48" alt="image" src="https://github.com/user-attachments/assets/97831780-75d7-446b-b7c6-bbb9c2147c35" />

Crie um novo container com o mesmo volume:  <br>
<img width="746" height="58" alt="image" src="https://github.com/user-attachments/assets/7cd971a1-9c7e-4462-bd91-1010acbbc995" />

Verifique se os dados persistiram:  <br>
<img width="835" height="64" alt="image" src="https://github.com/user-attachments/assets/06293913-4305-4e65-8723-b51fff5b6c0a" />

# 3.3 - Bind Mounts

Crie um diretório local:  <br>
<img width="593" height="251" alt="image" src="https://github.com/user-attachments/assets/9f5eae1b-e5a4-462c-8808-4160f8ceea30" />

Crie um arquivo index.html:  <br>
<img width="677" height="176" alt="image" src="https://github.com/user-attachments/assets/ec8a6894-ea49-4995-bb7a-abdc236eaf40" />

 Execute nginx com bind mount:  <br>
 <img width="1326" height="296" alt="image" src="https://github.com/user-attachments/assets/4a64a699-fe5e-4a71-ac41-330082cfb378" />

 Acesse no navegador:  <br>
 <img width="450" height="178" alt="image" src="https://github.com/user-attachments/assets/c6507405-6857-42d5-9d3a-a3305002e3bf" />

Modifique o index.html e veja as mudanças em tempo real:  <br>
<img width="592" height="195" alt="image" src="https://github.com/user-attachments/assets/86e90f73-4839-4c92-bcf5-a84b97e05e61" />

# 4.1 - Configurando com ENV

Crie um novo diretório:  <br>
<img width="687" height="278" alt="image" src="https://github.com/user-attachments/assets/710f6f1b-4107-4ca1-9ed7-d79ceb362958" />

Crie um arquivo app.py:  <br>
<img width="1132" height="443" alt="image" src="https://github.com/user-attachments/assets/3d6fd39c-bc12-4de2-a905-731f4670c31a" />

Crie um arquivo requirements.txt:  <br>
<img width="767" height="252" alt="image" src="https://github.com/user-attachments/assets/f5cad08c-062a-4a2c-9029-4448f281020b" />

# 4.2 - Dockerfile com ENV e ARG

Crie um Dockerfile:  <br>
<img width="1113" height="422" alt="image" src="https://github.com/user-attachments/assets/ea85d11e-65c9-43da-bdc1-fc2df8f7c4d9" />

Build com argumentos:  <br>
<img width="872" height="41" alt="image" src="https://github.com/user-attachments/assets/1c82694e-5ea1-49c8-a63d-85a0737adb6e" />

# 4.3 - Executando com Variáveis

Execute com variáveis inline:  <br>
<img width="869" height="86" alt="image" src="https://github.com/user-attachments/assets/63a20a32-b388-4465-bc8c-91965d183ad1" />

 Crie um arquivo .env:  <br>
 <img width="828" height="60" alt="image" src="https://github.com/user-attachments/assets/bcbbc053-8401-427e-b19c-1a08b8e0a299" />

Verifique as variáveis:  <br>
<img width="814" height="147" alt="image" src="https://github.com/user-attachments/assets/1007947b-816a-46ed-9b4c-963c6cfd552d" />

