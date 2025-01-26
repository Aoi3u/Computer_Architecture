# Computer Architecture

## 重要な語句

## 1. 命令セットアーキテクチャ
**命令セットアーキテクチャ（ISA)** は、コンピュータのハードウェアとソフトウェア間のインターフェースを定義する抽象的なモデル。RISC, CISCなどもこれに分類される。
### RISC
Reduced Instruction Set Computerはよく利用する命令のみに絞りハードを簡略する。特に、アセンブリでの命令が全て1ワードである。
### CISC
Complex Instruction Set Computerは複数ワードの命令も許す。
|  　　    | RISC | CISC |
| -------- | ------- |------- |
| ワード数  | １    |複数   |
|ハード | 簡略     |複雑    |
| ソフト    | 複雑（になりやすい）    |簡略（にできる）    |
## 2. ビットとバイトの大きさ(32 bit architecture)
1. 1 byte = 8 bits
2. 1 word = 32 bits
3. 1 half word = 16 bits
4. 1 double word = 64 bits
5. 1 int = 32 bits
6. 1 short int = 16 bits
7. (1 long = 64 bits)
8. 1 character = 16 bits
9. 1 漢字 = 16 bits
## 3. 基本的なアセンブリコマンド
