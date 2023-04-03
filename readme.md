## Introdução

**Boas vindas**

**Projeto base**
Nessa aula introdutória vamos apresentar o projeto base para podermos prosseguir com as aulas do módulo.

Link para o projeto: https://github.com/rocketseat-education/igniteshoesapp

**Conhecendo o projeto**
Nessa aula introdutória vamos apresentar e navegar pelo nosso projeto, conhecendo os componentes, as telas e as configurações que deixamos pré-criadas para agilizar o desenvolvimento da aplicação e o aprendizado do módulo

**Conceito de Push Notifications**
Nessa aula introdutória vamos mostrar mais a fundo os conceitos por volta das notificações push (Push Notification), para que elas servem, onde e quando devemos aplicar elas em nossas aplicações.

**Quiz - Introdução**

Questão 1. Sobre Push Notification, assinale a alternativa incorreta:
A Push Notification não é um recurso nativo dos sistemas operacionas mobile comuns (iOS e Android) e deve ser totalmente implementada do lado do app.

## Firebase Cloud Messaging

**Implementando no Android**
Nessa aula introdutória vamos falar um pouco de como irá funcionar a implementação do serviço de notificações no Android.

**Conhecendo o FCM**
Nessa aula introdutória vamos te apresentar o Firebase Cloud Messaging, o serviço que iremos utilizar para configurar o envio de notificações para nossos dispositivos Android.

**Criando um projeto no FCM**
Nessa aula prática vamos criar o projeto Android para envio das notificações dentro do console do Firebase, fazendo todas as configurações necessárias para que o FCM consiga se comunicar com nossa aplicação.

**Ativando o Firebase Cloud Messaging**
Nessa aula prática vamos ativar a funcionalidade de notificações dentro do console do Firebase, para que nosso app possa receber notificações.

**Quiz - Firebase Cloud Messaging**
Questão 1. Sobre FCM, assinale a alternativa incorreta:
Resposta
O FCM é um serviço pago que gerencia todo o envio de Push Notifications da sua aplicação, desde a SDK para cadastro dos dispositivos até dashboard com segmentação e envio automatizado de mensagens via web.

## One Signal

**Notificações com OneSignal**
Nessa aula introdutória vamos falar um pouco da plataforma que iremos utilizar para o gerenciamento do envio de notificações, o OneSignal

**Conhecendo o OneSignal**
Nessa aula introdutória vamos conhecer o OneSignal, entender como funciona e o que ele nos oferece para facilitar o gerenciamento de notificações.

**Criando projeto Android no One Signal**
Nessa aula prática vamos criar a aplicação Android dentro do OneSignal, utilizando as credencias que obtemos dentro do Firebase Cloud Messaging.

**Instalando o OneSignal no Projeto**

Nessa aula prática vamos iniciar a instalação da biblioteca do OneSignal no nosso projeto.

Vamos conhecer a estratégia de expo plugins para utilizarmos lib que utilizam código nativo.

Vamos também adicionar o id do app Android do OneSignal na nossa aplicação.

expo install onesignal-expo-plugin

npm install --save react-native-onesignal

**Quiz - OneSignal**
Questão 1. Sobre OneSignal, assinale a alternativa incorreta:
Resposta
É obrigatório utilizar o serviço de mensagens próprio do OneSignal, não podendo escolher um provedor externo (ex: FCM ou APNS)

## Expo Dev Client

**Código Nativo**
Nessa aula introdutória vamos conhecer um pouco sobre como nossa aplicação expo lida com bibliotecas que utilizam código nativo.

**Fluxos de trabalho**
Nessa aula introdutória vamos falar sobre os fluxos de trabalho que temos em uma aplicação React Native utilizando Expo. Vamos falar quais as principais diferenças entre eles e em que cenário cada um se aplica de melhor forma.

Vamos falar também sobre a estratégia que iremos utilizar nesse módulo que são as development builds, utilizando o expo-dev-client para executar nossa aplicação.

Tópicos relacionados à esta aula

**Expo Prebuild**
Nessa aula prática vamos utilizar a estratégia de Expo prebuild para podermos ter acesso as pastas nativas da nossa aplicação (android e ios), fazendo todas a configurações necessárias para este procedimento.

npx expo prebuild

**Configs Nativas**
Nessa aula introdutória vamos reforçar a importância de termos nosso ambiente nativo configurado na máquina para evitar que nossa aplicação tenha problemas no momento do build.

**Executando fora do Expo Go**
Nessa aula prática vamos mostrar como executar nossa aplicação por fora do Expo Go e rodar diretamente pelo código nativo da aplicação.

npx expo run:android

**Utilizando o Expo Dev Client**
Nessa aula prática vamos aprender como podemos utilizar o expo-dev-client que funciona como um ExpoGo customizado para executar nossa aplicação.

npx expo start --dev-client

**Conhecendo mais o Custom Development Client**

Nessa aula introdutória vamos falar um pouco mais a fundo sobre o expo-dev-client, de como ele funciona para criar um ExpoGo customizado somente com as libs nativas que podemos ter na nossa aplicação.

Vamos entender como essa funcionalidade facilita as configurações de código nativo.

**Quiz - Expo Dev Client**

Questão 1. Sobre os fluxos de trabalho com Expo, assinale a alternativa incorreta:
Resposta
O comando expo prebuild realiza a conversão de um fluxo Managed Workflow para Bare Workflow e o comando expo eject realiza a conversão de um projeto Expo para um projeto React Native CLI.

Questão 2. Ao instalar o plugin `onesignal-expo-plugin`, configurá-lo no `app.json` e executar o comando `expo prebuild` utilizamos o poder das development builds para realizar alterações nativas automaticamente e criar um cliente de desenvolvimento personalizado:
Resposta
Verdadeiro

## Apple Push Notification Service

**Conhecendo o APNS**
Nessa aula introdutória vamos falar um pouco sobre a Apple Push Notification Service, o serviço que vamos utilizar para que nossa aplicação iOS tenha acesso às notificações.

**Criando projeto no APNS**
Nessa aula prática vamos criar nosso projeto iOS dentro da plataforma do OneSignal utilizando o APNS.

**Gerando certificado Apple**
Nessa aula prática vamos aprender como podemos gerar um certificado de desenvolvedor da apple para podermos ter acesso ao serviço de notificações.

Vamos aprender como utilizar esse certificado para gerar a integração do APNS com o OneSignal.

**Executando e testando a integração**
Nessa aula prática vamos finalizar a configuração de integração da nossa aplicação iOS dentro do OneSignal, finalizando algumas configurações nativas dentro do XCode e adicionar o id do projeto iOS do OneSignal no nosso projeto.

**Quiz - Apple Push Notification Service**
Questão 1. Sobre o APNS, assinale a alternativa incorreta:
O APNS é um serviço que gerencia todo o envio de Push Notifications da sua aplicação, desde a SDK para cadastro dos dispositivos até dashboard com segmentação e envio automatizado de mensagens via web.

## Push Notification

**Enviando mensagens**
Nessa aula introdutória vamos dar continuidade com nossa aplicação, para a implementação das push notifications no nosso projeto

**Mensagens em background**
Nessa aula introdutória vamos falar um pouco sobre os estados da aplicação e como as notificações se comportam e cada um desses estados.

**Enviando a primeira mensagem no Android**
Nessa aula prática vamos conhecer melhor o painel do OneSignal e enviar nossa primeira notificação para nosso App Android.

Vamos aprender como podemos selecionar dispositivos para servirem como usuários de teste para essas notificações.

**Enviando a primeira mensagem no iOS**
Nessa aula prática iremos repetir o processo de envio de notificações só que dessa vez utilizando um dispositivo iOS para realização do teste de envio.

**Utilizando segmento de e-mail**
Nessa aula prática vamos aprender como podemos segmentar o envio de notificações com o OneSignal, utilizando o e-mail para enviar uma notificação para um usuário específico.

**Enviando mensagem para segmentos**
Nessa aula prática vamos aprender como utilizar os segmentos do OneSignal para realizar filtragens no momento do envio de notificações para melhorar a forma com que os usuário recebem essas notificações.

**Utilizando tags para identificar usuário**
Utilizando tags para identificar usuário

**Enviando mensagem filtrando por tag**
Nessa aula prática vamos aprender a como utilizar tags cadastradas no OneSignal e filtrar o envio de notificações para os usuários.

**Removendo tag**
Nessa aula prática vamos aprender como remover uma tag do OneSignal utilizando no app mobile.

**Deixando mensagem dinâmica com tags**
Nessa aula prática vamos aprender como utilizar o recurso de tags para personalizar notificações e melhorar a experiência do usuário.

**Prioridades e canais de notificação**
Nessa aula introdutória vamos conhecer um pouco sobre o conceito de prioridades e canais em notificações para aparelhos Android. Vamos entender como podemos utilizar esses recursos para melhorar o recebimento de notificações.

**Criando canais de notificação no Android**
Nessa aula prática vamos aprender como criar um canal de notificação para os dispositivos Android utilizando o painel do OneSignal.

**Enviando notificação para um canal**
Nessa aula prática vamos aprender como criar um canal de notificação para os dispositivos Android utilizando o painel do OneSignal.

**Conceito de foreground**
Nessa aula introdutória vamos aprender um pouco sobre o estado de foreground do nosso app e como as notificações se comportam nesse estado.

**Recebendo mensagem em foreground**
Nessa aula prática vamos aprender como podemos capturar os dados da notificação quando nosso app em primeiro plano, no estado de foreground.

**Utilizando componente de Notificação**
Nessa aula prática vamos utilizar o nosso componente Notification para exibir os dados de uma notificação que chega em foreground.

**Refatorando o componente de Notificação**
Nessa aula prática vamos refatorar o nosso component Notification, movendo toda a lógica de recebimento em foreground e tornando o componente clicável.

**Enviando dados na notificação**
Nessa aula prática vamos aprender como podemos enviar dados extras na notificação pelo OneSignal e receber no nosso app e exibir detalhes de um calçado.

**Verificando clique na notificação em background**
Nessa aula prática vamos aprender como podemos capturar o evento de clique do usuário em uma notificação que chegou enquanto o app está em estado de background.

**Adicionando botões de ações**
Nessa aula prática vamos aprender como utilizar a plataforma do OneSignal para criar botões de ação em um notificação para um dispositivo Android.

**Obtendo a opção selecionada**
Nessa aula prática vamos aprender a como utilizar o app para identificar o evento de clique do usuário em um botão de ação da notificação.

Vamos aprender como podemos receber esse evento e criar uma lógica para cada um dos botões que podem ser selecionados.

**Cronograma de Entrega de mensagens**
Nessa aula prática vamos conhecer o recurso de entrega de notificação agendada dentro do painel do OneSignal.

**Quiz - Push Notifications**

Questão 1. É possível enviar uma push notification diretamente da dashboard do OneSignal. Para isso, basta acessar o app e na aba `Dashboard` escolher a opção `New Message -> New Push`.
Resposta
Verdadeiro

Questão 2. Apesar do OneSignal gerenciar o envio de push notifications para múltiplas plataformas, não é possível enviar mensagens para múltiplas plataformas simultaneamente no mesmo projeto.
Resposta
Falso

Questão 3. Sobre as funcionalidades da dashboard do OneSignal, assinale a alternativa incorreta:
Resposta
O OneSignal permite que você segmente os usuários que deseja enviar a push notification, porém não é possível criar segmentos customizados.

Questão 4. Para utilizar dados dinâmicos no OneSignal, podemos cadastrar `tags` pelo dispositivo do usuário. Assinale a alternativa que não corresponde a uma forma de gerenciar as tags pela SDK:
Resposta
OneSignal.addTags()

## Deep Linking

**Iniciando Deep Linking**
Nessa aula introdutória vamos falar um pouco sobre o conceito de Deep Liking e como podemos aplicar essa funcionalidade em nosso app.

**Adicionando e listando schemes**
Nessa aula prática vamos explicar o que são os schemes da nossa aplicação e configurar o scheme na nossa aplicação.
Também vamos listar os schemes da nossa aplicação após finalizar todas as configurações.

Obs.: Caso sua máquina pedir para instalar o pacote uri-scheme, basta aceitar digitando y e confirmando.

npx uri-scheme list

**Executando Deep Linking**
Nessa aula prática vamos aprender como testar o Deep Linking da nossa aplicação através do terminal para quando precisarmos realizar testes de linking na nossa aplicação.

npx uri-scheme open com.rocketseat.igniteshoes://

**Deep Linking na Push Notification**
Nessa aula prática vamos aprender como podemos utilizar nossos schemes para realizar um Deep Linking dentro de uma Push Notification.

**Configurando navegação do Deep Linking**
Nessa aula prática iremos criar nossa configuração de linking dentro do nosso app para que o React Navigation consiga receber parâmetros e navegar o usuário para a tela correta.

**Passando parâmetro no Deep Linking**
Nessa aula prática vamos aprender como montar uma rota de Deep Linking passando parâmetros.

Vamos testar esse link com parâmetros e ver se todos eles estão sendo repassados corretamente.
npx expo install expo-linking

**Deep Linking com parâmetro na Push Notification**
Nessa aula prática vamos acessar o painel do OneSignal e alterar a nossa launch URL para uma url com parâmetros.

**Tratando Deep Linking com App em primeiro plano**
Nessa aula prática vamos refatorar nosso componente de Notification, corrigindo a abertura do deep link no cenário de estar com o app em primeiro plano.

**Conceito de carrinho abandonado**
Nessa aula introdutória vamos falar um pouco sobre o conceito de carrinho abandonado e como podemos utilizar desse tipo de conceito para segmentar notificações para os usuário.

**Criando tag para carrinho**
Nessa aula prática vamos implementar uma função que irá criar pelo nosso app uma tag para o carrinho.

Vamos criar essa tag adicionando de forma dinâmica a quantidade de itens no carrinho do usuário.

**Removendo item do carrinho**
Nessa aula prática vamos adicionar a função de criar/atualizar a tag de carrinho dentro da função que remove itens do carrinho do usuário.

**Criando o segmento de carrinho abandonado**
Nessa aula prática vamos acessar o painel do OneSignal e criar a segmentação para filtrar e identificar os usuário que possuem itens no carrinho e ainda não finalizaram a compra para enviar uma notificação específica para esses usuários.

**Enviando Notificações para Segmento**
Ness aula prática vamos enviar notificações para usuários que se encaixam no segmento de carrinho abandonado.

**Utilizando tag no conteúdo da notificação**
Nessa aula prática vamos relembrar como podemos utilizar as tags para personalizar o conteúdo da mensagem de uma notificação com os valores armazenados em uma tag.

**Adicionando Badge no menu**
Nessa aula prática vamos aprender como podemos utilizar um badge para indicar visualmente se o carrinho possui itens e quantos itens estão no carrinho.

**Encerramento do módulo**
Nessa aula vamos te parabenizar por ter chegado até o final do módulo e ter concluído mais uma etapa e ter adquirido mais um conhecimento em React Native.

**Quiz - Deep Linking**
Questão 1. Utilizamos o deep linking para abrir uma tela específica do app, podendo inclusive passar parâmetros e valores.
Resposta
Verdadeiro

Questão 2. Sobre a configuração do deep linking no React Navigation, assinale a opção que corretamente configura esse recurso:
Resposta
const config = {
screens: {
Chat: 'feed/:sort',
Profile: 'user',
},
};

const linking = {
prefixes: ['https://example.com', 'example://'],
config,
};

<NavigationContainer linking={linking}>
	{/* content */}
</NavigationContainer>

Questão 3. Sobre Deep Linking, assinale a alternativa incorreta:
Resposta
O Deep linking consegue redirecionar apenas schemes específicos do app mobile, não sendo possível tratar, por exemplo, o redirecionamento de links https.
