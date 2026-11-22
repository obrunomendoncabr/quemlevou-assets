# quemlevou-assets

Arquivos visuais do @quemlevou, pra gerar os cards de qualquer lugar (inclusive sem o computador do Bruno ligado).

- `crests/` escudos dos clubes, em PNG com fundo transparente. O nome é a sigla usada nos scripts (`FLA.png`, `BOC.png`). Clubes de estaduais levam a UF (`FLA_PI.png`).
- `fonts/` Chakra Petch (Bold e SemiBold) e Martian Mono Bold, só o alfabeto latino. Não têm o caractere →, então a seta da paginação é desenhada à mão quando o card é gerado com essas fontes. Os arquivos originais completos ficam no computador do Bruno.

- `flags/` bandeiras em PNG 640×480, com o código ISO em minúsculas (`br.png`, `ar.png`, `gb-eng.png`). Vieram do pacote flag-icons (licença MIT). As históricas `it-reino` (Reino da Itália) e `hu-1949` (Hungria de 1954) não estão aqui e precisam ser desenhadas quando forem usadas.

Pra usar com os scripts, aponta a variável `QL_ASSETS` pra esta pasta.

Escudo novo: coloca o PNG em `crests/` com a sigla e faz commit.
