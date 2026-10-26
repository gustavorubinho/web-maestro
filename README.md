# 🎼 Web Maestro: Dies Irae (Maestro VR Experience)

Uma experiência web imersiva em **primeira pessoa** inspirada em **Maestro VR** e **Five Nights at Freddy's**, onde você assume o papel de regente (Maestro) à frente de uma orquestra sinfônica completa e coro, regendo a icônica obra *Dies Irae* (*Messa da Requiem*) de Giuseppe Verdi.

---

## 🎮 Mecânicas e Controles

* **Câmera Panorâmica Estilo FNAF**:
  - Movimente o mouse horizontalmente pela tela para girar suavemente a cabeça do maestro e olhar para diferentes seções da orquestra (primeiros violinos à esquerda, violoncelos e trompas à direita).
  - Inclui inércia cinematográfica e efeito de profundidade com **parallax 3D** entre o palco e a estante do maestro.
* **Foto Realista de Concerto**:
  - Fundo fotográfico hiper-realista em alta resolução capturado da perspectiva exata do pódio.
  - Botão no menu superior para alternar entre diferentes palcos reais (*POV Maestro*, *Verdi Requiem ao Vivo*, *Seattle Symphony Hall* ou *Sala 3D Acústica*).
* **Notas em Branco Sólido Nítido (Zero Glow)**:
  - Discos brancos opacos com contorno preto nítido e setas vetoriais de precisão cirúrgica, sem borrões ou gradientes neon para garantir timing e visibilidade ideais.
* **Gestos de Regência**:
  - **Corte Direcional (Swipe)**: Arraste a batuta na direção da seta (`⬇`, `⬆`, `⬅`, `➡`) no momento em que ela cruzar a barra dourada.
  - **Ataque / Clique (Click)**: Clique com o botão esquerdo nos ataques secos e impactos tutti (*BAM!*).
  - **Manter a Ópera (Hold / Fermata)**: Pressione e segure o botão esquerdo para sustentar os acordes prolongados do coro e metais.
* **Áudio Autêntico e Puro**:
  - Gravação original da Orquestra e Coro do Teatro alla Scala tocando Giuseppe Verdi (*Messa da Requiem - Dies Irae*).
  - Sem efeitos sonoros sintéticos intrusivos no acerto/erro, preservando a fidelidade da música.

---

## 🚀 Como Executar

Basta abrir o arquivo `index.html` em qualquer navegador web moderno (Chrome, Edge, Firefox, Brave). Não requer dependências externas nem instalação de pacotes.

```bash
# Clone o repositório
git clone https://github.com/gustavorubinho/web-maestro.git

# Acesse o diretório
cd web-maestro

# Abra no navegador
start index.html
```

---

## 📂 Estrutura de Arquivos

* `index.html`: Código-fonte completo (HTML5 Canvas 2D, física de câmera FNAF, motor de partitura e renderizador de batuta).
* `dies_irae.ogg`: Gravação autêntica de *Dies Irae* de Giuseppe Verdi.
* `orchestra_bg.jpg`: Foto realista em perspectiva do pódio.
* `verdi_requiem_stage.jpg`: Fotografia de palco de apresentação ao vivo de Verdi Requiem.
* `seattle_symphony.jpg`: Panorama fotográfico do auditório sinfônico.
