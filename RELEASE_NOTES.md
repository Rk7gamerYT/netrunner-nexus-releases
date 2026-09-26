## Netrunner Nexus 0.4.0 Preview 1

Instalador para Windows 10/11 x64. Instala no perfil do usuário e não precisa de permissão de administrador.

### Novidades

- Proteção completa contra fingerprinting: Canvas, WebGL, AudioContext, fontes, hardware (núcleos/memória) e tela/fuso horário, configurável em Privacidade (Padrão, Estrito ou Personalizado).
- Serviço de atualização automática: verifica a versão mais recente periodicamente, baixa e confere hash e assinatura digital do instalador antes de qualquer coisa rodar, e sempre pede confirmação antes de fechar o Nexus e instalar.
- Correções de segurança internas identificadas numa auditoria de código, incluindo reforço da integridade das atualizações e da gravação de arquivos baixados.
- Gerenciador de downloads integrado em uma aba, com pausar, retomar, cancelar e abrir arquivos.
- Cofre de senhas local separado por perfil, criptografado pelo Windows.
- Windows Hello para revelar, editar ou excluir senhas salvas (Windows 11).
- Busca, edição e exclusão das credenciais salvas, além de gerador de senhas fortes.
- Tema e navegação visualmente consistentes nas páginas internas.
- Preferência por Vulkan com Direct3D como alternativa quando Vulkan não estiver disponível.
- DNS seguro e política configurável de proteção WebRTC.

### Limites desta prévia

O cadastro de senhas é manual. Captura de logins e preenchimento automático em sites não estão disponíveis. As senhas não são sincronizadas nem exportáveis.

O instalador não tem assinatura digital de editor; o Windows pode informar que o publicador é desconhecido. Confira o SHA-256 anexado antes de instalar.

O pacote inclui a licença proprietária do Nexus e os avisos e créditos do CEF e Chromium. Componentes de terceiros continuam sujeitos às próprias licenças.
