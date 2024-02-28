## Laboratório 5 - Explore a IA generativa com o Microsoft Copilot
# Uma das melhores ferramentes de IA na minha opnião é a geração de imagens com perfeição, assim como veremos a seguir.

- Abra https://copilot.microsoft.com e entre com sua conta pessoal da Microsoft.

![image](https://github.com/WesleyHorquen/microsoft-ia-dio-lab05/assets/89001286/7eb0360d-c1fd-4aef-b4ed-bb102f9e9257)
- Logo abaixo podemos descrever como queremos a imagem.

![image](https://github.com/WesleyHorquen/microsoft-ia-dio-lab05/assets/89001286/8fc99968-126e-4104-a433-fc4d6ab13a24)

- o **Copilot** irá começar a trabalhar na geração da imagem
 
![image](https://github.com/WesleyHorquen/microsoft-ia-dio-lab05/assets/89001286/41beb2f9-0e36-4ba7-9dd2-6c4286179189)
- Obtemos quatro resultados para o nosso pedido, apesar de se parecerem muito neste caso

![image](https://github.com/WesleyHorquen/microsoft-ia-dio-lab05/assets/89001286/164a40dd-067d-49ae-8420-6b58ce631ae6)
- Podemos ir além e imaginar um pouco mais fora da curva e deixar o trabalho pesado para a IA

![image](https://github.com/WesleyHorquen/microsoft-ia-dio-lab05/assets/89001286/5e70187e-98df-4bf2-920c-85e031c63566)
![image](https://github.com/WesleyHorquen/microsoft-ia-dio-lab05/assets/89001286/da0e26e1-2fb6-4626-b26d-ffd401a61f7d)


# Reconhecendo texto a partir de uma imagem com o **AI Azure Services**

- Abra o portal do azure em https://portal.azure.com e acesse sua conta e vamos em **Criar um recurso**

![image](https://github.com/WesleyHorquen/microsoft-ia-dio-lab05/assets/89001286/81a0842a-8d22-4793-87c3-718ff7f5c94f)
- Clicamos na categoria **IA + Machine Learning** e procuramos o **IA Services** e clicamos em **Criar**

![image](https://github.com/WesleyHorquen/microsoft-ia-dio-lab05/assets/89001286/2cf9ef18-89d4-4ef2-8932-b1ff23bdab5b)
- Vamos preencher o **Grupo de Recursos** com um novo, ou um existente, **Nome** colocaremos um de nossa preferência, **Tipo de preço** deixaremos o **Standard SO** depois basta selecionar o **box** e clicar em **Examinar + Criar** e após **Criar** novamente

![image](https://github.com/WesleyHorquen/microsoft-ia-dio-lab05/assets/89001286/47ed2e3f-5ff7-411a-a4ae-6639fec2b225)
- Depois de terminado aparecerá o seguinte

![image](https://github.com/WesleyHorquen/microsoft-ia-dio-lab05/assets/89001286/79385cc2-a971-4663-8196-65c5164cb620)

# Em uma nova guia vamos abrir o **Vision Studio** https://portal.vision.cognitive.azure.com/?azure-portal=true

- Vamos clicar em **View all resources**

![image](https://github.com/WesleyHorquen/microsoft-ia-dio-lab05/assets/89001286/ecc1cb0d-9826-42b7-be46-33a366d2102d)
- Vamos clicar em **Refresh** após selecionar o nosso **Recurso** e depois logo abaixo em **Select as default resource**
- Feito isso, vamos abrir uma nova aba https://portal.vision.cognitive.azure.com/gallery/featured clicar em **Optical character recognition** e depois em **Extract text from images**

![image](https://github.com/WesleyHorquen/microsoft-ia-dio-lab05/assets/89001286/9e413717-b898-4bfd-bdec-3be20580f66b)
- Selecionamos o **box**

![image](https://github.com/WesleyHorquen/microsoft-ia-dio-lab05/assets/89001286/16dc42f3-723d-4d29-8f30-58e9d2f4695d)
- Agora só fazer o Upload de nossa foto

![image](https://github.com/WesleyHorquen/microsoft-ia-dio-lab05/assets/89001286/d2edd13e-6e25-40ed-bf80-83339d573735)
- Irá aparecer a nossa foto, e ao lado o que a IA identificou escrito nela

![image](https://github.com/WesleyHorquen/microsoft-ia-dio-lab05/assets/89001286/d35b23a8-f438-4ce7-9573-e4c8aeddf5fb)
![image](https://github.com/WesleyHorquen/microsoft-ia-dio-lab05/assets/89001286/3af42c82-98c0-4afb-9abc-08b69295467c)

