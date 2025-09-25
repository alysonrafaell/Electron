
#Electron

🌩️ Projeto Desktop - Aplicativo de Clima
Um aplicativo de clima simples e preciso construído com Electron e Node.js que utiliza a API do OpenWeatherMap.

✨ Recursos
Busca por Cidade: Visualize o clima atual de qualquer cidade do mundo.

Unidades Configuráveis: Alterne entre Celsius (°C) e Fahrenheit (°F).

Tray Icon: O aplicativo fica minimizado na bandeja do sistema para acesso rápido.

Atalhos Globais: Utilize atalhos de teclado para controle rápido da janela.

Prevent Power Save: Impede que o computador entre em modo de suspensão enquanto o aplicativo estiver ativo (recurso configurável).

🚀 Começando
Siga estas instruções para obter uma cópia de trabalho do projeto em sua máquina local.

Pré-requisitos
Você precisa ter o Node.js e o npm (ou yarn) instalados.

1. Clonar o Repositório
Bash

git clone []
cd projeto-desktop

2. Instalar Dependências
Instale todas as dependências do projeto listadas no package.json.

Bash

npm install
# ou
yarn install
3. Executar o Aplicativo
Inicie o aplicativo Electron em modo de desenvolvimento.

Bash

npm start
⚙️ Configurações e Atalhos
O aplicativo oferece várias formas de interação:

Configurações (Dentro do App)
Você pode configurar a cidade padrão e a unidade de temperatura acessando a tela de Configurações (geralmente por um botão de engrenagem).

Atalhos Globais
Atalho	Ação
Ctrl/Cmd+Q	Fecha o aplicativo (encerra completamente).
Ctrl/Cmd+N	Foca no campo de busca de nova cidade.
Ctrl/Cmd+Left	Move a janela para o canto esquerdo da tela.
Ctrl/Cmd+Right	Move a janela para o canto direito da tela.

Exportar para as Planilhas
🏗️ Construção (Build)
Para gerar um instalador ou um executável da aplicação, você pode usar os scripts de build configurados com electron-builder.

Para Windows
Bash

npm run build-win
Para Outros Sistemas
Bash

npm run build
O executável/instalador final será gerado na pasta dist/.

🤝 Contribuição
Sinta-se à vontade para sugerir melhorias, reportar bugs ou contribuir com código.

Faça um Fork do projeto.

Crie uma branch para sua feature (git checkout -b feature/AmazingFeature).

Commit suas mudanças (git commit -m 'Add some AmazingFeature').

Faça um Push para a branch (git push origin feature/AmazingFeature).

Abra um Pull Request.

📝 Licença
Distribuído sob a licença MIT. Veja o arquivo LICENSE (se houver) para mais informações.

Desenvolvido por: Alyson Rafael Gomes Da Silva
