# Pulso: estado desejado

O diretório k8s contém o Deployment e o Service observados pelo Argo CD.
argocd/application.yaml cadastra a Application no namespace argocd.

Use seu login no repoURL e na imagem. A imagem precisa de uma tag de SHA completo já publicada no GHCR.
O namespace de destino é pulso. Antes de qualquer comando, confira o contexto kind-gitops-lab.
Versão e commit vêm da imagem: não fixe APP_VERSION no Deployment desta demonstração.
