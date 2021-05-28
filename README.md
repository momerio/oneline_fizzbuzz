# oneline_fizzbuzz
Pythonワンラインチャレンジ FizzBuzz問題

## <FizzBuzz ルール>
1. 3で割り切れる→Fizz
1. 5で割り切れる→Buzz
1. 3かつ5で割り切れる→FizzBuzz
1. 上記すべて以外→数字を出力

→ 答えは "Fizz Buzz FizzBuzz 2" と出力される．

`[print(n) for n in [3, 5, 15, 2] if not (n % 3 == 0 and n % 5 == 0) or print("FizzBuzz") if not (n % 3 == 0) or print("Fizz") if not (n % 5 == 0) or print("Buzz")]`
