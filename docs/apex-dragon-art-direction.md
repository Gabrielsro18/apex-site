# APEX — Direção de arte e contrato do dragão 3D

## Referência principal
Imagem original enviada pelo usuário em 22/11/2026 (dragão APEX vermelho, preto e dourado, pousado em rocha vulcânica). Esta imagem é a referência de identidade e proporções; não deve ser substituída por dragões genéricos.

## Silhueta obrigatória
- Dragão quadrúpede, maciço, de perfil três-quartos, cabeça à direita.
- Pescoço longo e curvado; cabeça estreita, focinho alongado, chifres e espinhos orientados para trás.
- Asas enormes, membranas com recortes irregulares e pontas afiadas, abertas para trás e à esquerda.
- Cauda longa, musculosa e curva, avançando pelo primeiro plano.
- Patas fortes e garras douradas agarrando a pedra.

## Materiais
- Escamas pequenas e sobrepostas, negras com vermelho profundo.
- Bordas metálicas douradas em chifres, espinhos e nervuras das asas.
- Fissuras incandescentes vermelho-laranja entre placas, sem deixar o corpo inteiramente luminoso.
- Olhos vermelhos brilhantes, sem trocar o formato anatômico da cabeça.
- Membrana das asas escura, translúcida apenas nas bordas, com veios vermelho-escuros.

## Cenário e emblema
- Montanha de obsidiana fraturada, fendas de lava, névoa volumétrica.
- Céu escuro com nuvens vermelho-fogo e contraluz quente.
- Castelo gótico distante, à direita, em silhueta.
- Grande emblema A metálico dourado, joia vermelha no ápice, anel de runas vermelhas.
- O emblema é elemento de composição e deve continuar reconhecível no desfecho.

## Contrato técnico do modelo
- Arquivo final: assets/apex-dragon.glb, glTF 2.0 binário, texturas embutidas.
- Eixo Y para cima; dragão voltado ao eixo +X; origem próxima ao centro do tronco.
- Malha com materiais PBR e normais consistentes; sem dependências externas.
- Rig recomendado: root, spine, neck, head, jaw, tail segments, wing_L, wing_R, forelegs, hindlegs.
- Animações desejadas: idle_perched, takeoff, flight_loop, landing, final_pose.
- Evitar animação de câmera dentro do GLB: a câmera permanece sob controle do site.
- Otimizar para navegadores móveis, com versão de menor complexidade quando necessário.

## Sequência de aprovação
1. Comparação estática lado a lado com a referência: silhueta, cores, asas, cabeça, cauda.
2. Modelo no visualizador isolado; confirmar escala, orientação e materiais.
3. Testar rig e animações sem alterar o laboratório funcional.
4. Integrar ao laboratório de rolagem, com opção de retornar ao modelo anterior.
5. Só depois considerar promoção ao site principal.

## Critérios de rejeição
- Dragão formado por esferas e cones visíveis como geometria final.
- Cabeça, asas ou cauda de proporções diferentes da referência.
- Vermelho puro e dourado chapado sem texturas de escamas e metal.
- Substituição da cena vulcânica por fundo genérico.
- Falha de carregamento que deixe a tela vazia.

## Estado
Documento de especificação. O modelo GLB ainda não foi produzido nem validado.
