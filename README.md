# Battery-Finder-Program-create

## project 概要

![スクリーンショット 2022-11-23 17 42 11](https://user-images.githubusercontent.com/101037787/203503258-ecda290e-6489-420f-b64f-093748a9e1ec.png)


あなたは電池を量産するエンジニアリングチームに所属しており、顧客に電池を推奨するプログラムを開発する仕事を任されています。


今、カメラ用電池のデータセットとカメラのデータセットが与えられています。電池のデータセットには、電池名、容量（Ah）、電圧、最大放電電流（A）、終止電圧が含まれており、カメラのデータセットには、メーカー、製品名、消費電力（Wh ワット時間）が含まれています。


電力とは、単位時間に電流がする仕事（量）のことを指します。国際単位系（SI）においては、ワット（W）が単位として用いられ、1 ワットは毎秒 1 ジュールに等しいエネルギーを生じさせる仕事率と定義されます。


電気工学の分野では、仕事率である電力（W）は、電流（I）と電位（V）を用いて、P = I * V として表すことができます。国際単位系（SI）では、電流はアンペア（A）で表され、1 アンペアの電流で 1 秒間に運ばれる電荷が 1 クーロンとなります。


それでは例を見てみましょう。テレビの電源電圧が 120V で、電流が 1.2A の場合、消費電力は P = I * V を用いて、P = 120 * 1.2 = 144W となります。同様に、電圧が 14.4V で、満充電時電池容量が 6.6Ah（A / hr）の電池は、14.4V × 6.6Ah = 95Wh（W / hr）の電力容量を持ちます。仮にその電池を消費電力が 50W のカメラに使用した場合、95 / 50 ＝ 1.9 時間（114分）持続可能であることを意味します。


チームは充電池のショートや破裂しないように安全対策を構築する必要があります。電池は使用していくうちに電圧が低下し、そのまま使い続けると、電極が溶けたり破裂したりする原因となります。安全に使用できる最低電圧を終止電圧と言います。終止電圧時に電池が供給できる電力は、終止電圧 × 最大放電電流 で計算でき、カメラの消費電力を上回るようにしなければなりません。


例えば、電池の最大放電電流が 6.3A で 12V が終止電圧の場合、終止電圧時の最大放電電力は 6.3A × 12V = 76W となり 76W 以上消費するカメラには使用できません。


メーカーと製品名を選択し、その後アクセサリー（USB やライト等）用に、0-100W の範囲で消費電力が入力可能なアプリケーションを作成してください。総消費電力に基づいて、カメラセットと互換性のあるすべての電池を表示し、さらに満充電時にどれほど電池が持続するか表示してください。
## URL
 https://daitennn.github.io/Battery-Finder-Program-create/

## 使用言語
<ol>
 <li>HTML</li>
 <li>CSS</li>
 <li>Javascript</li>
</ol>
