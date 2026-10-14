# Verificação SisQuali

Página pública de verificação de autenticidade dos documentos emitidos pelo **SisQuali**, sistema de acompanhamento dos servidores do IFRN em qualificação (DIDEPE/DIGPE/IFRN).

**Endereço:** https://erasmojpo.github.io/sisquali-verificacao/

## Como funciona

- Cada relatório emitido pelo SisQuali traz um código (`SQ-AAAA-XXXX-XXXX`) e um QR Code com um selo assinado digitalmente (ECDSA P-256).
- A chave privada fica somente no SisQuali. Esta página contém apenas a **chave pública**, que serve só para conferir assinaturas.
- A verificação é feita no navegador de quem consulta: a página não acessa banco de dados nem envia o documento para lugar nenhum.
- Formas de verificar: ler o QR Code (que abre esta página já com o selo), enviar o PDF do relatório, enviar uma foto do QR Code ou colar o código.

## Limites

O selo comprova a origem do documento no SisQuali e que os dados do resumo assinado não foram alterados. Não substitui assinatura com certificado digital (ICP-Brasil, gov.br ou SUAP). A conferência do arquivo completo (impressão digital SHA-256) é feita internamente na Administração do SisQuali.

© DIDEPE/DIGPE/IFRN. Todos os direitos reservados.
