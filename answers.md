
以下に「超初級Pythonコーディング50本ノック📕📈」の答えの部分をMarkdown形式でご用意しました。各問題に対応する解答コードを確認して、学習を進めてくださいね。😊🐍

超初級Pythonコーディング50本ノック 📕📈 - 答え一覧

問題1. 挨拶を表示しよう！👋

# 解答:
print("Hello, Python!")

問題2. 足し算をしてみよう ➕➕

# 解答:
a = 5
b = 3
print(a + b)

問題3. 名前を入力しよう 📝

# 解答:
name = input("名前を入力してください: ")
print(f"こんにちは、{name}さん！")

問題4. 2つの数の最大値を見つけよう 🔝

# 解答:
a = 10
b = 20
if a > b:
    print(a)
else:
    print(b)

問題5. 偶数か奇数かを判定しよう 🔢

# 解答:
number = int(input("数字を入力してください: "))
if number % 2 == 0:
    print("偶数です。")
else:
    print("奇数です。")

問題6. リストの合計を計算しよう ➕

# 解答:
numbers = [1, 2, 3, 4, 5]
total = sum(numbers)
print(total)

問題7. 繰り返し処理でカウントしよう 🔄

# 解答:
for i in range(1, 11):
    print(i)

問題8. 簡単な計算機を作ろう 🧮

# 解答:
a = float(input("1つ目の数字を入力してください: "))
b = float(input("2つ目の数字を入力してください: "))
op = input("演算子を入力してください (+, -, *, /): ")

if op == '+':
    print(a + b)
elif op == '-':
    print(a - b)
elif op == '*':
    print(a * b)
elif op == '/':
    if b != 0:
        print(a / b)
    else:
        print("0で割ることはできません。")
else:
    print("無効な演算子です。")

問題9. リストから最大値を見つけよう 🌟

# 解答:
numbers = [10, 20, 30, 40, 50]
max_num = max(numbers)
print(max_num)

問題10. フィボナッチ数列を表示しよう 🔢🔢

# 解答:
n_terms = 10
a, b = 0, 1
for _ in range(n_terms):
    print(a)
    a, b = b, a + b

問題11. 文字列を反転しよう 🔄🔠

# 解答:
text = input("文字列を入力してください: ")
reversed_text = text[::-1]
print(reversed_text)

問題12. リストの要素を追加しよう ➕

# 解答:
numbers = []
for _ in range(5):
    num = int(input("数字を入力してください: "))
    numbers.append(num)
print(numbers)

問題13. 辞書を使ってみよう 🗂️

# 解答:
students = {
    "Alice": 20,
    "Bob": 22,
    "Charlie": 23
}

for name, age in students.items():
    print(f"{name} は {age} 歳です。")

問題14. タプルの基本 📋

# 解答:
numbers = (10, 20, 30, 40, 50)
print(numbers[2])  # インデックスは0から始まります

問題15. 集合で重複をなくそう 🔄🚫

# 解答:
numbers = [1, 2, 2, 3, 4, 4, 5]
unique_numbers = set(numbers)
print(unique_numbers)

問題16. 条件付きリスト内包表記 📜

# 解答:
even_numbers = [x for x in range(1, 21) if x % 2 == 0]
print(even_numbers)

問題17. ファイルに書き込もう 📁✍️

# 解答:
with open("sample.txt", "w") as file:
    file.write("Hello, File!")

問題18. ファイルを読み込もう 📖🔍

# 解答:
with open("sample.txt", "r") as file:
    content = file.read()
    print(content)

問題19. 簡単なカレンダーを表示しよう 📅

# 解答:
import calendar

print(calendar.month(2024, 12))

問題20. ランダムな数を生成しよう 🎲

# 解答:
import random

rand_num = random.randint(1, 100)
print(rand_num)

問題21. リストの平均を計算しよう 📊

# 解答:
numbers = [10, 20, 30, 40, 50]
average = sum(numbers) / len(numbers)
print(average)

問題22. ユーザーの年齢をチェックしよう 🎂

# 解答:
age = int(input("年齢を入力してください: "))
if age >= 18:
    print("成人です。")
else:
    print("未成年です。")

問題23. リストの並び替えをしよう 🔄📋

# 解答:
numbers = [5, 2, 9, 1, 5, 6]
numbers.sort()
print(numbers)

問題24. 複数の条件を使おう 🧩

# 解答:
number = int(input("数字を入力してください: "))
if 10 < number < 20:
    print("10より大きく20より小さいです。")
else:
    print("条件に合いません。")

問題25. リストの中から特定の要素を探そう 🔍

# 解答:
fruits = ['apple', 'banana', 'cherry']
if 'banana' in fruits:
    print("バナナが見つかりました！")
else:
    print("バナナは見つかりませんでした。")

問題26. 数字を文字列に変換しよう 🔢➡️🔠

# 解答:
number = 123
str_number = str(number)
print(str_number)

問題27. リストの要素を逆順にしよう 🔄📋

# 解答:
numbers = [1, 2, 3, 4, 5]
reversed_numbers = numbers[::-1]
print(reversed_numbers)

問題28. 文字列の長さを測ろう 📏✍️

# 解答:
text = input("文字列を入力してください: ")
length = len(text)
print(f"文字列の長さは {length} 文字です。")

問題29. 2つのリストを結合しよう ➕📋📋

# 解答:
list1 = [1, 2, 3]
list2 = [4, 5, 6]
combined_list = list1 + list2
print(combined_list)

問題30. 辞書から値を取得しよう 🗂️🔍

# 解答:
person = {'name': 'Alice', 'age': 25}
print(f"名前: {person['name']}")
print(f"年齢: {person['age']}")

問題31. 最大値と最小値を見つけよう 🔝🔻

# 解答:
numbers = [3, 1, 4, 1, 5, 9, 2, 6, 5]
max_num = max(numbers)
min_num = min(numbers)
print(f"最大値: {max_num}")
print(f"最小値: {min_num}")

問題32. リストの要素をカウントしよう 📊🔢

# 解答:
fruits = ['apple', 'banana', 'apple', 'cherry', 'banana', 'cherry', 'cherry']
count = fruits.count('cherry')
print(f"'cherry' の出現回数: {count} 回")

問題33. 素数を判定しよう 🔍🔢

# 解答:
number = int(input("数字を入力してください: "))
if number > 1:
    for i in range(2, number):
        if (number % i) == 0:
            print(f"{number} は素数ではありません。")
            break
    else:
        print(f"{number} は素数です。")
else:
    print(f"{number} は素数ではありません。")

問題34. フィボナッチ数列の特定の項を取得しよう 🔢🔢

# 解答:
n = 10
a, b = 0, 1
for _ in range(n - 1):
    a, b = b, a + b
print(b)

問題35. 簡単なアラーム時計を作ろう ⏰🔔

# 解答:
import time

seconds = int(input("秒数を入力してください: "))
time.sleep(seconds)
print("時間です！")

問題36. リストの重複を取り除こう 🚫🔄

# 解答:
numbers = [1, 2, 2, 3, 4, 4, 5]
unique_numbers = list(set(numbers))
print(unique_numbers)

問題37. ユーザーのパスワードをチェックしよう 🔐

# 解答:
password = input("パスワードを入力してください: ")
if password == "python123":
    print("アクセス許可")
else:
    print("アクセス拒否")

問題38. 文字列を大文字にしよう 🔠

# 解答:
text = input("文字列を入力してください: ")
uppercase_text = text.upper()
print(uppercase_text)

問題39. 文字列を小文字にしよう 🔡

# 解答:
text = input("文字列を入力してください: ")
lowercase_text = text.lower()
print(lowercase_text)

問題40. リストをシャッフルしよう 🎲📋

# 解答:
import random

numbers = [1, 2, 3, 4, 5]
random.shuffle(numbers)
print(numbers)

問題41. 最初のn項をリストにしよう 📜🔢

# 解答:
n = int(input("nを入力してください: "))
numbers = list(range(1, n + 1))
print(numbers)

問題42. フィボナッチ数列のリストを作ろう 🔢📋

# 解答:
n_terms = 10
fib_list = []
a, b = 0, 1
for _ in range(n_terms):
    fib_list.append(a)
    a, b = b, a + b
print(fib_list)

問題43. ユーザーの入力を繰り返そう 🔄📝

# 解答:
while True:
    name = input("名前を入力してください（終了するには '終了' と入力）: ")
    if name == "終了":
        print("プログラムを終了します。")
        break
    print(f"こんにちは、{name}さん！")

問題44. 簡単な電卓アプリを作ろう 🧮💻

# 解答:
def calculator():
    try:
        num1 = float(input("1つ目の数字を入力してください: "))
        op = input("演算子を入力してください (+, -, *, /): ")
        num2 = float(input("2つ目の数字を入力してください: "))
        
        if op == '+':
            return num1 + num2
        elif op == '-':
            return num1 - num2
        elif op == '*':
            return num1 * num2
        elif op == '/':
            return num1 / num2
        else:
            return "無効な演算子です。"
    except ZeroDivisionError:
        return "0で割ることはできません。"
    except ValueError:
        return "無効な入力です。"

result = calculator()
print(f"結果: {result}")

問題45. リストから重複を数えよう 🔢➗

# 解答:
from collections import Counter

numbers = [1, 2, 2, 3, 3, 3, 4, 4, 4, 4]
count = Counter(numbers)
print(count)

問題46. リストを二つに分割しよう 🔗🔗

# 解答:
numbers = [1, 2, 3, 4, 5, 6]
half = len(numbers) // 2
first_half = numbers[:half]
second_half = numbers[half:]
print("前半:", first_half)
print("後半:", second_half)

問題47. リストの要素を検索しよう 🔍📋

# 解答:
colors = ['red', 'green', 'blue', 'yellow']
if 'blue' in colors:
    print("ブルーが見つかりました！")
else:
    print("ブルーは見つかりませんでした。")

問題48. 二つのリストを比較しよう ⚖️📋📋

# 解答:
list1 = [1, 2, 3]
list2 = [1, 2, 4]

diff = [x for x in list1 if x not in list2] + [x for x in list2 if x not in list1]
print("異なる要素:", diff)

問題49. 文字列を分割しよう ✂️🔠

# 解答:
sentence = input("文章を入力してください: ")
words = sentence.split()
print(words)

問題50. お疲れ様！総まとめクイズ 🎉🎓

# 解答:
while True:
    name = input("名前を入力してください: ")
    if name == "終了":
        print("プログラムを終了します。")
        break
    age_input = input("年齢を入力してください: ")
    try:
        age = int(age_input)
        if age >= 18:
            print(f"{name}さんは成人です。")
        else:
            print(f"{name}さんは未成年です。")
    except ValueError:
        print("無効な年齢です。数字を入力してください。")
    print("---")

おわりに 🌟

お疲れ様でした！👏
50本ノックの答えを通じて、Pythonの基礎をしっかりと確認できたでしょうか？📈
自分でコードを書き、実行してみることで理解が深まります。🚀
さらに挑戦的な課題に取り組んで、スキルを磨いていきましょう！

Happy Coding! 🐍✨
