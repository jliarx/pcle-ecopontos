PCLE — Landing page de ecopontos
================================

Arquivos
- index.html: página completa (HTML, CSS e JavaScript).
- README.txt: este guia.

O que já funciona
- Mapa interativo Leaflet com base OpenStreetMap.
- Lista de pontos, busca e filtros.
- Clique em um marcador ou item da lista para exibir detalhes.
- Botão para abrir rota no Google Maps.
- Seções Sobre e Galeria.

IMPORTANTE — antes de divulgar
Os quatro locais incluídos no código são DADOS DEMONSTRATIVOS. Eles não representam ecopontos confirmados e não devem ser divulgados como locais reais.
1. Pesquise pontos reais na cidade escolhida usando fontes oficiais da prefeitura, cooperativas ou operadores de logística reversa.
2. Confirme endereço, coordenadas, materiais aceitos, horário e contato.
3. No index.html, procure o comentário "DADOS DE DEMONSTRAÇÃO" e edite o array `points`.
   Cada ponto usa: id, name, address, lat, lng, category, materials, hours e contact.
4. Atualize os links sociais do rodapé: procure `href="#"` e substitua pelos endereços corretos.
5. Complete os créditos acadêmicos no rodapé e a descrição do projeto.
6. As imagens são carregadas de URLs externas do Unsplash; é necessária conexão com a internet.

Como testar no computador
- Abra o arquivo index.html no navegador. Para evitar restrições locais em alguns navegadores, você pode usar a extensão Live Server do Visual Studio Code.
- A página depende de internet para carregar o mapa, as fontes de mapa e as imagens.

Publicar gratuitamente pelo Netlify (fluxo simples)
1. Extraia o ZIP para uma pasta no computador.
2. Entre em https://app.netlify.com/ e crie uma conta ou faça login.
3. No painel, procure a opção de adicionar um novo site e publicar/deploy manual (a nomenclatura pode mudar).
4. Arraste a pasta que contém o index.html, ou a pasta extraída, para a área de deploy manual quando essa opção estiver disponível.
5. Aguarde a publicação e abra o endereço .netlify.app gerado.
6. Teste no celular e computador.

Alternativa: GitHub Pages
1. Crie uma conta em https://github.com/.
2. Crie um repositório público chamado `pcle-ecopontos`.
3. Envie o arquivo index.html para a raiz do repositório.
4. Abra Settings > Pages, selecione a publicação a partir da branch principal (normalmente `main`) e pasta `/ (root)`, e salve.
5. Aguarde a URL publicada no formato https://SEU-USUARIO.github.io/pcle-ecopontos/.

Limitações
- É uma página estática; não há painel administrativo nem banco de dados.
- Para atualizar os ecopontos, edite o array `points` no código e publique novamente.
- OpenStreetMap e Netlify/GitHub Pages têm termos e limites de uso; consulte suas políticas para uso continuado ou de maior tráfego.
- O mapa requer conexão à internet.
