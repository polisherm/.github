# .github

polisherm のリポジトリに共通の既定ファイルを置く。

ここに置いたファイルは、同じファイルを自分で持っていないリポジトリで、既定として使われる。
private のリポジトリにも使われる。
仕組みは GitHub の [Creating a default community health file](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file) にある。

## 置いているもの

- [PULL_REQUEST_TEMPLATE.md](PULL_REQUEST_TEMPLATE.md): pull request の本文のテンプレート

## 変えるとき

テンプレートを変えるときは、ここだけを直す。
各リポジトリに `.github/PULL_REQUEST_TEMPLATE.md` を置くと、そのリポジトリではここのテンプレートが使われなくなる。
