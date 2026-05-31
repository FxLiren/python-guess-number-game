import random

def guess_number_game():
    number = random.randint(1, 100)
    guess = 0
    count = 0

    print("=" * 40)
    print("🎯 猜數字遊戲開始！（1 ~ 100）")
    print("系統已隨機生成一個數字，請開始猜測！")
    print("=" * 40)

    while guess != number:
        try:
            guess = int(input("請輸入你的猜測："))
            count += 1

            if guess > number:
                print("📈 太大了")
            elif guess < number:
                print("📉 太小了")
            else:
                print("\n🎉 恭喜你猜對了！")
                print(f"正確答案是：{number}")
                print(f"你總共猜了 {count} 次")
                print("=" * 40)

        except ValueError:
            print("⚠ 請輸入有效的數字！")

# 執行遊戲
if __name__ == "__main__":
    guess_number_game()
