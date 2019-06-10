# Zemi

# 内容

自分がゼミで扱って実装したコードを載せています。1つ目はInZemiはABMというシュミレーションモデルを作った時のもので、2つ目のfinal-summer-homeworkは初期の頃にオブジェクト思考のプログラムを作るように言われた時のものです。3つ目はHayatoYamaguchi_0623_homeworkで、これはオブジェクト指向の原価計算を行ったものです。


# InZemi

ABM個人(Agent)が独自の動きをしていて、各々のグループの中で自分より良いパフォーマンスを持った個人の真似をしていって、個人のパフォーマンスをあげるというものです。

・mainクラス→実際に実行

・Agentクラス→個人のAgentの定義

・AgentGroupクラス→個人が属するAgentGroupの定義

・briefクラス→個人が持つ考え（０と１の行列によって与えられ、この考えが実際の答えとどれくらい合っているかによってスコア（パフォーマンス）が決まる）

・Metricsクラス→briefの中の０と１を決める

・ Settingクラス→ここでパラメータの変更

・showGraphsクラス→二つのパラメータを設定してそのパラメータによる結果の違いをグラフで出力

・showNetworksクラス→個々人のネットワークがどのように繋がっているか（それぞれ誰から学ぶか）を定義するクラス

・totalCalculateクラス→実際にその試行全体を何回か回して回した結果のスコアやcsvファイルの出力


# final-summer-homework

ポケモンのダメージ計算を自動でやり、最後まで自動でポケモンバトルをするプログラムです。

・Mainクラス→ポケモンの設定や技の設定

・CalcDamageクラス→ダメージの計算

・Battleクラス→実際にバトルを行うクラス

・Moveクラス→技の設定

・Pokemonクラス→ポケモンの設定



# HayatoYamaguchi_0623_homework
中身を見る時は.javaを見てください
名前が酷いことになってますが、原価計算をプログラミングを用いて行なっております。人とグループで行ったもののため人の名前が入っています。

