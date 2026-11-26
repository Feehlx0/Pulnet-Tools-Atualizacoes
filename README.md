<h1 align="center">Pulnet Tools</h1>

<p align="center">
  Central de ferramentas da <strong>Pulnet Tecnologia</strong> para manutenção e diagnóstico do Windows.
</p>

<p align="center">
  <a href="https://github.com/Feehlx0/Pulnet-Tools-Atualizacoes/releases/latest"><img src="https://img.shields.io/github/v/release/Feehlx0/Pulnet-Tools-Atualizacoes?label=vers%C3%A3o&color=00B3CF" alt="Versão mais recente"></a>
  <img src="https://img.shields.io/badge/Windows-10%20e%2011-001557" alt="Windows 10 e 11">
</p>

---

Este repositório guarda **apenas os instaladores publicados** do Pulnet Tools. É daqui que o aplicativo baixa as suas atualizações.

## ⬇️ Baixar

1. Abra a [versão mais recente](https://github.com/Feehlx0/Pulnet-Tools-Atualizacoes/releases/latest).
2. Em **Assets**, baixe o arquivo `PulnetTools-Setup-<versão>.exe`.
3. Execute o arquivo e siga o assistente de instalação.

A instalação é feita só para o seu usuário, **não precisa de senha de administrador** e cria um atalho no Menu Iniciar. Para remover, use **Configurações do Windows → Aplicativos**.

> **Aviso do Windows na primeira execução:** o instalador ainda não tem assinatura digital, então o Windows SmartScreen pode mostrar "O Windows protegeu o computador". Se você baixou o arquivo desta página, clique em **Mais informações → Executar assim mesmo**.

### Requisitos

- Windows 10 (versão 1809 ou mais recente) ou Windows 11, 64 bits.

## 🧰 O que o Pulnet Tools faz

| Ferramenta | Para que serve |
|---|---|
| **Limpeza de arquivos temporários** | Mostra quanto espaço os arquivos temporários ocupam e libera esse espaço com a sua confirmação. |
| **Limpeza de cache dos navegadores** | Remove o cache do Microsoft Edge e do Google Chrome. |
| **Espaço em disco** | Mostra o que está ocupando espaço no computador, com relatório em PDF. |
| **Meu computador** | Reúne as informações do computador para facilitar o atendimento, com relatório em PDF. |
| **Programas que iniciam com o Windows** | Desativa o que deixa o início do computador lento (dá para ligar de volta). |
| **Programas instalados** | Lista os programas do computador com tamanho e data. |
| **Destravar a impressora** | Cancela documentos presos na fila e reinicia o serviço de impressão. |
| **Diagnóstico de internet** | Descobre se o problema está no computador, no roteador, no DNS ou no provedor, e mede a velocidade. |
| **Verificação e reparo do Windows** | Confere e repara arquivos do próprio Windows (SFC e DISM). |
| **Histórico de saúde** | Acompanha disco, espaço, processador e memória e avisa quando algo não vai bem (opcional). |

## 🔒 Segurança e privacidade

- **Nada é apagado sem a sua confirmação.** O app nunca começa uma limpeza sozinho.
- **Seus arquivos pessoais nunca são tocados:** Documentos, Área de Trabalho, Downloads, fotos, vídeos, músicas, backups e pastas do OneDrive/nuvem ficam de fora.
- **Não roda como administrador.** Só os reparos do Windows e o reinício do serviço de impressão pedem permissão, pelo aviso normal do Windows, a cada uso. Nenhuma senha é guardada.
- **Nenhum dado do computador é enviado.** O app só usa a internet quando você pede: para verificar atualizações (nesta página) e no diagnóstico de internet.
- **Tudo fica registrado** no próprio computador, para consulta do suporte.

## 🔄 Atualizações

Com o Pulnet Tools aberto, vá em **Configurações → Sobre o Pulnet Tools → Verificar atualizações**. O app consulta esta página, baixa a versão nova e, antes de instalar, confere se o arquivo é exatamente o publicado aqui (impressão digital SHA-256). Depois ele fecha, atualiza e abre de novo sozinho.

> Computadores com a versão 1.1.0 ou anterior não têm o botão de atualização: instale a versão mais recente manualmente uma vez, pelo link acima.

### Conferir o arquivo manualmente (opcional)

Cada versão traz um arquivo `.sha256` com a impressão digital do instalador. Para conferir, abra o PowerShell na pasta onde o instalador foi baixado:

```powershell
Get-FileHash .\PulnetTools-Setup-<versão>.exe -Algorithm SHA256
```

O resultado deve ser igual ao código dentro do arquivo `.sha256`.

## 📞 Suporte

Dúvidas ou problemas? Fale com o suporte da **Pulnet Tecnologia**.

---

<sub>Pulnet Tools é software proprietário da Pulnet Tecnologia. Todos os direitos reservados.</sub>
