
# InstallUpdates 

Este documento descreve um script de atualização desenvolvido para o sistema operacional Windows. O script é projetado para facilitar o processo de atualização do sistema operacional e dos softwares instalados, garantindo que o ambiente do usuário esteja sempre atualizado com as versões mais recentes.


## Configurações iniciais

Para executar este Script você precisa verificar a política de execução do seu sistema operacional Windows. Para isto, utilize o seguinte comando no PowerShell:

```bash
  Get-ExecutionPolicy
```

Caso o retorno seja diferente de Unrestricted, altere a configuração da política de execução para o valor informado acima:

```bash
  Set-ExecutionPolicy
```





## Instalação e execução

 1) Para fazer o download desse Script de Git Clone neste repositório em uma pasta de sua preferência.

 2) Importante! Por questões de segurança execute este Script com o modo Administrador.

```bash
  .\"InstalUpdates.ps1"
```


## Autores

- [Tracking Digital Solution](https://github.com/Tracking-Digital-Solution/Tracking-Digital-Solution.git)

