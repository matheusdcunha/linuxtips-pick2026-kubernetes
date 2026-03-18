# Resumo Day 02

Nesse dia nos aprofundamos mais sobre **Pods**.

## Principais comandos

Começamos os principais comandos para ver os Pods como o `kubectl get pods` e para inspecionar o Pod como `kubectl describe pods pod-name`.

Também vimos sobre comandos para entrar dentro do container do Pod. 

- `kubectl exec` - Esse comando ele cria um novo processo dentro do container.
- `kubectl attach` - Esse comando ele se anexa ao processo principal do container.

## Manifesto

Agora começamos ver como criar manifestos, os principais atributos e como criar Pods com mais de um container.

Estudamos uma função primordial no K8s que é a **limitação de recursos** de um container. E por fim vimos brevemente sobre volumes.

