- 👋 Hi, I’m @Prince709max
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Prince709max/Prince709max is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import random
maxn = 10
n = random.randint(1, maxn)
print('Welcome to guess the number game!')
print('Guess the number from  to %d' % maxn)
guess = None
while guess != n:
    guess = int(input('Your try: '))
    if guess > n:
        print('10')
    if guess < n:
        print('5')

print('Congratulations, you won!')


