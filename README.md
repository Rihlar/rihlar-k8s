# rihlar-k8s
rihlar を argocd でデプロイする時に使うリポジトリ

## セットアップ方法
- rihlar namespace を作成する
- secret_template を secret.yaml に変更して適切な設定をする
- https://github.com/Rihlar/rihlar-k8s を argocd に設定する