## インフラ構成図
<img width="690" alt="image" src="https://github.com/endodaigakuseitaishi/deploy_to_ecs/assets/89571473/f8bc17d5-b38c-440e-a39b-c49c9c39da11">

### 詳細
- [ ] VPC作成
- [ ] public subnet✖︎２, private subnet✖︎1作成
- [ ] インターネットゲートウェイをアタッチ
- [ ] エンドポイントを作成
  パブリックサブネットがインターネットゲートウェイを経由した外部通信,VPC内の通信,エンドポイントの通信
- [ ] RDSを作成
     - セキュリティグループを設定(tcp)
- [ ] ALBを作成
  - SSL証明書の発行
  - セキュリティグループを設定(http, https)
- [ ] localでdockerをbuild
- [ ] ECRでリポジトリを作成
- [ ] イメージをpush
- [ ] ECSのタスク定義
- [ ] クラスターを作成
- [ ] サービスを作成
- [ ] health_check成功、ALBのエンドポイントにブラウザアクセス成功

===========2023年5月現在、ここまで===========


## API側
- [ ] ruby on railsでtodo管理アプリのAPIを作成
- [ ] RSpecなし

## フロント側
- [ ] reactをJSで記述
