# NodeJs_Console_Title

## Resimler

![image](https://user-images.githubusercontent.com/63351166/213913116-2b69b2ad-0b2e-442e-9fd2-464a4d390851.png)
![image](https://user-images.githubusercontent.com/63351166/213913142-c5a22a9d-1cc6-4250-8273-f22fcb45205d.png)

## Kod

```
function console_title(x) {
    if (process.platform == 'win32') {
		process.title = x;
	} else {
		process.stdout.write('\x1b]2;' + x + '\x1b\x5c');
	}
}
console_title("Trendyol Ürün Çekici - github.com/fastuptime");
```

## Tech Stack

**Server:** Node

---
- ✨ [Destek İçin](https://fastuptime.com) <br>
- 💕 [Discord](https://fastuptime.com/discord)<br>
- 🎖️ [FasterHost Technology](https://fasterhost.tech/)<br>
- ✨ İletişim için [Tıkla!](mailto:fastuptime@gmail.com)<br>

# License
- Its protected by Creative Commons ([CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/))

<a href="https://creativecommons.org/licenses/by-nc-sa/4.0/" title="BYNCSA40"><img src="https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png"></a>
