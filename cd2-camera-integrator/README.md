

## CD2 Camera Integrator

Componente de câmera universal para React.

Projetado com foco em câmeras Android e iOS.
Funciona com webcams padrão também.

Veja [este](http://caniuse.com/#feat=stream) para compatibilidade do navegador.

Observação: o WebRTC é compatível apenas com conexões seguras. Então você precisa servi-lo de https. Você pode testar e depurar no Chrome a partir do host local (isso não funciona no Safari).

### Funcionalidades

- Solução de câmera compatível com dispositivos móveis (testada em iOS e Android)
- Elemento de vídeo é totalmente responsivo
  - você pode configurar o parâmetro para cobrir seu contêiner
  - você pode definir aspectRatio de visualização: 16/9, 4/3, 1/1, ...
- Tirar foto para arquivo jpeg base64 - com a mesma proporção de visualização, com resolução FullHD (ou máximo suportado pela câmera).
- Trabalhando com webcams padrão ou outros dispositivos de entrada de vídeo
- Suporta foco automático
- Troca de câmeras de face/ambiente (com seu próprio botão)
- Detecta o número de câmeras
- A câmera frontal é espelhada, o ambiente não
- funções públicas para tirar fotos, trocar de câmera e obter o número de câmeras
- biblioteca de texto datilografado
- Possibilidade e adequado para integração com Apis externas

### Configuração:
##### Baixe o projeto do repositório e abra seu editor de preferência.
##### Precisa ter previamente configurado o react, node, axios e express no seu ambiente

### `npm start`

Executa o aplicativo no modo de produção.
Abra [http://sua_urlProducao](http://localhost:3000) para visualizá-lo no navegador.

A página será recarregada se você fizer edições.
Você também verá quaisquer erros de lint no console.

### `npm server`

Executa o aplicativo no modo de desenvolvimento.
Abra [http://localhost:3000](http://localhost:3000) para visualizá-lo no navegador.

A página será recarregada se você fizer edições.
Você também verá quaisquer erros de lint no console.

### `npm test`

Inicia o executor de teste no modo de observação interativo.
Consulte a seção sobre [execução de testes](https://facebook.github.io/create-react-app/docs/running-tests) para obter mais informações.

### `npm run build`

Cria o aplicativo para produção na pasta `build`.
Ele empacota corretamente o React no modo de produção e otimiza a compilação para obter o melhor desempenho.

A compilação é minificada e os nomes dos arquivos incluem os hashes.
Seu aplicativo está pronto para ser implantado!

Consulte a seção sobre [implantação](https://facebook.github.io/create-react-app/docs/deployment) para obter mais informações.

### `npm run eject`

**Nota: esta é uma operação unidirecional. Depois de 'ejetar', você não pode voltar!**

Se você não estiver satisfeito com a ferramenta de construção e opções de configuração, você pode `ejetar` a qualquer momento. Este comando removerá a dependência de compilação única do seu projeto.

Em vez disso, ele copiará todos os arquivos de configuração e as dependências transitivas (Webpack, Babel, ESLint, etc) diretamente para o seu projeto, para que você tenha controle total sobre eles. Todos os comandos, exceto `eject`, ainda funcionarão, mas apontarão para os scripts copiados para que você possa ajustá-los. Neste ponto, você está por conta própria.

Você nunca precisa usar `eject`. O conjunto de recursos selecionados é adequado para implantações pequenas e médias, e você não deve se sentir obrigado a usar esse recurso. No entanto, entendemos que esta ferramenta não seria útil se você não pudesse personalizá-la quando estivesse pronto para ela