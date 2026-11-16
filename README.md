# PAA-RBE 2026/27 — Plano Anual de Atividades da Biblioteca Escolar

Aplicação web, num único ficheiro (`index.html`), que recria o modelo Excel PAA-RBE 2026/27 para preenchimento no navegador.

- As seis folhas do modelo, com as mesmas fórmulas, listas de validação e comentários.
- Os dados ficam guardados apenas no navegador de quem preenche (localStorage); nada é enviado para a Internet.
- «Descarregar Excel» gera o ficheiro .xlsx completo (fórmulas, formatação, gráficos e proteção); «Importar Excel» carrega um PAA deste modelo já preenchido.
- Registos de sessões na Monitorização: em cada atividade, regista-se a data e as turmas de cada sessão e a app soma tudo e preenche a linha, seguindo as regras do modelo (cada turma conta uma vez; o n.º de sessões é a média por turma). A lista de turmas preenche-se uma vez, na folha «0. Informação geral».
- Sem dependências externas.

Recomenda-se descarregar o Excel com regularidade, como cópia de segurança.
