### Rubocop設定ファイル

### 使用方法
サブモジュールとして追加して利用する。
```shell
$ git submodule add https://github.com/mocaberos/rubocop.git ./vendor/rubocop
```
設定を継承して使用する
```yaml
# rails用
inherit_from: ./vendor/rubocop/rails.rubocop.yml
```
```yaml
# gem用
inherit_from: ./vendor/rubocop/gem.rubocop.yml
```
