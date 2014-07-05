Specs
=====

A repository of CocoaPods (cocoapods.org) specifications.

Para fazer update no PodSpec, usar as regras:

Alterar o PodSpec na pasta GCKit
Copiar o PosSpec alterado p/ a pasta GCKitSpecs
Fazer upload dos 2 commits
No terminal, em qq lugar, rodar o comando: pod repo update
Depois q terminar, rodar o teste: pod repo lint

Para atualizar o projeto de testes .. no terminal, ir a pasta dele .. e rodar: pod update


——

Para instalar  Pod privado num projeto novo:
pod repo add (seu spec do seu git)
pod repo update
pod install
Seu podfile tem q ter o gckit la
