# More versatile mechanoid

- メカノイド全般実行可能な作業の種類を増やすMod
- 実行可能になる作業は多岐にわたるため、以下のドキュメントをそれぞれ参照してください
  - [新たに実行可能になった作業一覧(Core+DLC)](enable_tasks.md)

## 詳細

「メカノイドは実行不可」と指定されている **作業** に対してパッチを当てて、メカノイドにも実行可能な作業にしている。

- rimworldにおいては **仕事** の下に具体的な **作業** が所属する形になっている
  - 例: 仕事:`採掘`
    - 作業: `掘削`, `ボーリング`
      - ※ボーリング : 深部ドリルマシンによる採掘
- 作業側で 「メカノイドは実行不可」 と指定されている場合がある
  - 例: `ボーリング`
- 「メカノイドの作業可否」が明確に指定されていない作業もある
  - 例: `掘削`
  - おそらく 未指定 == 実行可能
    - トンネラーは掘削が出来ている実例がある

## MID-SAVE

- 途中導入
  - 問題ないと思われます
- 途中除去
  - 本Modによって実行可能になった作業を実施しているメカノイドがいるとエラーが出るかもしれません

## CONFLICT

- [More Mechanitor Mechs 2.0](https://steamcommunity.com/sharedfiles/filedetails/?id=3296057117)
  - 本Modの変更と同等の処理が含まれているため、本Mod側を使用する意義が薄い
- [Paramedics Feed Prisoners](https://steamcommunity.com/sharedfiles/filedetails/?id=2904976042) を筆頭とした **メカノイドが行える仕事の種類を増やすMod全般**
  - 本Modの変更と同等の処理が含まれているため、併用する意義が薄い

## NOTICE

本Modは [BSD 3-Clause “New” or “Revised” License](LICENSE) [(日本語参考訳)](https://licenses.opensource.jp/BSD-3-Clause/BSD-3-Clause.html) で提供されています。

謝辞および使用している素材・ライブラリは [NOTICE.md](NOTICE.md) に記載してあります。

プルリクエストおよびイシューについては [リポジトリに対する各種貢献についての指針](https://github.com/piet-rian/.github/blob/main/CONTRIBUTING.md) を参照した上でお願いします。
