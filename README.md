# 🕵️‍♂️ Operação Detetives da Saúde: Arboviroses & Vacinas
### Atividade de Extensão da Semana Universitária (SEMUNI) — Universidade de Brasília (UnB)

Aplicação web gamificada e acervo de materiais pedagógicos sobre o combate a **Dengue, Zika e Chikungunya**, identificação do vetor *Aedes aegypti*, prevenção e desmistificação de fake news sobre as vacinas no SUS.

---

## 🎮 O Jogo Web (`index.html`)

O jogo foi desenvolvido em **Single File** (HTML5 + Tailwind CSS + Vanilla JS + Web Audio API nativo) com design arcade investigativo (CSI/D.I.V.):
- **Mascote Reativo ("Agente Glóbulo"):** Reações dinâmicas e falas com base nos acertos e erros.
- **Carimbo 3D ("SLAM!"):** Animações tridimensionais nas perguntas de *Fato ou Fake*.
- **Combo Streak de Fogo:** Bônus multiplicador de pontos para acertos consecutivos.
- **Power-up 50:50:** Botão de rádio comunicador da Central que elimina duas alternativas erradas.
- **Áudio 100% Nativo:** Sons sintetizados via Web Audio API sem necessidade de arquivos de áudio externos.
- **Condecoração e Confetes:** Emissão do distintivo oficial de Perito de Elite com explosão de confetes via `canvas-confetti`.

---

## 📂 Acervo de Materiais da Oficina (Prontos para Impressão)

Abra o arquivo **[`hub_materiais.html`](hub_materiais.html)** no navegador para acessar o portal com todos os materiais:

| Arquivo | Descrição |
| :--- | :--- |
| **[`hub_materiais.html`](hub_materiais.html)** | Portal unificado de navegação e impressão de todos os materiais. |
| **[`index.html`](index.html)** | Jogo web arcade mobile para acesso via QR Code da balinha. |
| **[`roteiro_monitores.html`](roteiro_monitores.html)** | Roteiro cronometrado de 15 min, scripts e protocolo corta-giro. |
| **[`cartoes_fato_ou_fake.html`](cartoes_fato_ou_fake.html)** | 6 Dossiês frente e verso com carimbos e justificativas científicas (Estação 4). |
| **[`caso_clinico_peritos.html`](caso_clinico_peritos.html)** | Prontuário de Marina, 15 cartas de evidências e mapa da mesa (Estação 5). |
| **[`passaporte_e_medalhas.html`](passaporte_e_medalhas.html)** | Passaporte individual A5 e cartela de distintivos redondos de 5 cm. |
| **[`panfleto_triptico.html`](panfleto_triptico.html)** | Folder tríptico A4 para os pais com tabela de sinais de alarme da UPA. |

---

## 🚀 Como Executar ou Hospedar na Vercel

### Opção 1: Vercel (Recomendada)
Como o arquivo principal é `index.html`, basta importar este repositório no dashboard da [Vercel](https://vercel.com):
1. Faça login na Vercel com sua conta GitHub.
2. Clique em **Add New... ➔ Project**.
3. Selecione o repositório `LucasTheHacker/batista-extensao-semuni`.
4. Clique em **Deploy**. O site estará no ar em segundos com HTTPS gratuito!

### Opção 2: Local
Basta dar um duplo clique em qualquer um dos arquivos `.html` para abrir diretamente no seu navegador.
