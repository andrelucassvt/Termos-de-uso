# Termos de Uso – Clean Mac for Devs

**Última atualização:** 29/03/2026

Bem-vindo ao **Clean Mac for Devs**! Antes de utilizar o aplicativo, leia atentamente estes Termos de Uso. Ao acessar ou utilizar o aplicativo, você concorda com os termos aqui descritos.

---

## 1. Identificação

**Clean Mac for Devs** é um aplicativo para macOS desenvolvido de forma independente. O aplicativo auxilia desenvolvedores a recuperar espaço em disco removendo artefatos de build, caches e pastas de dependências de projetos de software.

---

## 2. Aceitação dos Termos

Ao baixar, instalar ou utilizar o Clean Mac for Devs, você declara que leu, compreendeu e concorda com estes Termos de Uso. Caso não concorde com qualquer disposição aqui prevista, não utilize o aplicativo.

---

## 3. Descrição do Serviço

O Clean Mac for Devs oferece ao desenvolvedor:

- Detecção automática de projetos Flutter, Xcode, Node.js, Python, Rust, Android, React Native e React;
- Remoção de artefatos de build, caches e pastas de dependências selecionados pelo usuário;
- Exibição de resumo com número de itens removidos e espaço em disco liberado;
- Persistência de caminhos selecionados por meio de bookmarks seguros do sistema operacional;
- Interface disponível em inglês e português brasileiro (pt-BR).

O aplicativo funciona inteiramente de forma local no dispositivo do usuário. Nenhum arquivo, dado de projeto ou informação pessoal é transmitido a servidores externos.

---

## 4. Requisitos do Sistema

- macOS 14.0 (Sonoma) ou superior;
- Permissão de acesso às pastas concedida pelo próprio usuário.

---

## 5. Uso do Aplicativo

### 5.1. Uso Permitido

O aplicativo destina-se exclusivamente ao uso pessoal ou profissional de desenvolvedores de software para fins de gerenciamento do espaço em disco do próprio dispositivo.

### 5.2. Restrições de Uso

Você concorda em não:

- Utilizar o aplicativo para fins ilegais ou não autorizados;
- Redistribuir, revender ou sublicenciar o aplicativo sem autorização expressa;
- Modificar, adaptar, descompilar, realizar engenharia reversa ou derivar obras do aplicativo;
- Tentar contornar ou remover as proteções tecnológicas implementadas;
- Transmitir vírus, malware ou qualquer código de natureza destrutiva por meio do aplicativo.

---

## 6. Responsabilidade do Usuário pela Operação de Limpeza

O Clean Mac for Devs remove permanentemente arquivos e pastas dos projetos selecionados. **O usuário é o único responsável pela seleção das pastas e pela execução das operações de limpeza.**

Antes de executar qualquer operação, certifique-se de que:

- Você possui backup ou controle de versão (ex.: Git) dos projetos afetados;
- Compreende quais artefatos serão removidos em cada tecnologia suportada;
- Os projetos selecionados não estão abertos ou em uso por outras ferramentas.

Os arquivos removidos pelo aplicativo **não são enviados para a Lixeira** e não podem ser recuperados pelo aplicativo após a exclusão.

---

## 7. Artefatos Removidos por Tecnologia

O aplicativo remove exclusivamente os artefatos listados abaixo, conforme a tecnologia identificada em cada projeto:

| Tecnologia | Artefatos removidos |
|---|---|
| **Flutter** | `build/`, `.dart_tool/`, `pubspec.lock`, `ios/Pods/`, `ios/Podfile.lock`, `ios/Gemfile.lock` |
| **Xcode** | `DerivedData/`, `Index/`, `Archives/` |
| **Node.js** | `node_modules/`, `dist/`, `build/`, `.next/`, `.nuxt/`, `.svelte-kit/`, `.turbo/`, `coverage/`, `.parcel-cache/` |
| **Python** | `venv/`, `.venv/`, `env/`, `.env/`, `.pytest_cache/`, `dist/`, `build/`, `.mypy_cache/`, `.ruff_cache/`, `__pycache__/` |
| **Rust** | `target/` |
| **Android** | `.gradle/`, `build/`, `app/build/`, `.kotlin/`, `captures/`, `.cxx/` |
| **React** | `node_modules/`, `build/`, `dist/`, `.next/`, `.cache/`, `coverage/`, `.parcel-cache/`, `.turbo/`, `storybook-static/` |
| **React Native** | `node_modules/`, `android/.gradle/`, `android/build/`, `android/app/build/`, `ios/Pods/`, `ios/build/`, `.metro/`, `coverage/` |

Todos os artefatos listados são regeneráveis pelas ferramentas de build de cada tecnologia.

---

## 8. Sandbox e Permissões de Acesso

O aplicativo opera com **App Sandbox** habilitado. Todo acesso ao sistema de arquivos depende de permissão explícita concedida pelo usuário por meio das caixas de diálogo nativas do macOS. Os caminhos autorizados são armazenados localmente no dispositivo via **security-scoped bookmarks**, sem coleta ou transmissão de dados.

---

## 9. Propriedade Intelectual

O aplicativo Clean Mac for Devs, incluindo seu código-fonte, design, ícones, marcas e demais materiais, é protegido pelas leis de propriedade intelectual aplicáveis. É vedada a reprodução, distribuição ou criação de obras derivadas sem autorização expressa do desenvolvedor.

---

## 10. Disponibilidade e Atualizações

O aplicativo é distribuído no estado em que se encontra. O desenvolvedor poderá, a seu critério:

- Lançar atualizações com novas funcionalidades, correções ou mudanças nas tecnologias suportadas;
- Descontinuar o aplicativo ou funcionalidades específicas sem aviso prévio.

Recomenda-se manter o aplicativo atualizado para garantir compatibilidade com as versões mais recentes do macOS e das ferramentas de desenvolvimento suportadas.

---

## 11. Limitação de Responsabilidade

O aplicativo é fornecido **"no estado em que se encontra"**, sem garantias de qualquer natureza, expressas ou implícitas. Na extensão máxima permitida pela legislação aplicável, o desenvolvedor não será responsável por:

- Perda ou corrupção de arquivos decorrente do uso do aplicativo;
- Danos diretos, indiretos ou consequentes resultantes do uso ou da impossibilidade de uso do aplicativo;
- Incompatibilidades com versões específicas de ferramentas ou sistemas operacionais.

O uso do aplicativo é de inteira responsabilidade do usuário.

---

## 12. Privacidade

O aplicativo não coleta, armazena nem transmite dados pessoais ou de projetos a servidores externos. Para informações detalhadas, consulte a **Política de Privacidade** disponível junto ao aplicativo.

---

## 13. Alterações nos Termos de Uso

O desenvolvedor reserva-se o direito de modificar estes Termos de Uso a qualquer momento. As alterações serão publicadas junto ao aplicativo ou em seu repositório oficial com a data de atualização. O uso continuado do aplicativo após as modificações constitui aceitação dos novos termos.

---

## 14. Legislação Aplicável

Estes Termos de Uso são regidos pela legislação brasileira. Fica eleito o foro da comarca do domicílio do desenvolvedor para dirimir quaisquer controvérsias oriundas desta relação, com renúncia a qualquer outro, por mais privilegiado que seja.

---

## 15. Contato

**email:** andrelucassvt99@gmail.com

---

*Clean Mac for Devs — Libere espaço. Construa mais.*
