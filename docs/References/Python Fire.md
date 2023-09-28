---
category:
  - "[[Software]]"
language: Python
open source: Yes
link: https://github.com/google/python-fire
rating: "7"
price: "0"
purchased:
  "{ date }": 
tags:
  - products
---

CLI for the lazy. Just uses function arguments.
```
import fire
main(arg1, arg2):
	print("blah")

if __name__ == __main__:
	fire.Fire(main)
```

```
python main.py --arg1 a --arg2 b
```