# Bandit Note

## Password
```bash
ssh bandit{}@bandit.labs.overthewire.org -p 2220
```

| User | Password |
|------|----------|
| bandit0 | bandit0 |
| bandit1 | ... |
| bandit2 | 263JGJPfgU6LtdEvgfWU1XP5yac29mFx |
| bandit3 | MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx |
| bandit4 | 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ |
| bandit5 | 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw |
| bandit6 | HWasnPhtq9AVKe0dmk45nxy20cvUa6EG |


## Bandit 4 -> 5
`file /*`
Dùng để xem định dạng file, do hint là *human-readable*. Sẽ ra được file khác vs những files còn lại, do là ASCII text -> human đọc đc -> dùng lệnh `cat`. 

## Bandit 5 -> 6
`find . -size 1033c`
- `.`: current directory
- `-size`: tìm file có kích thước 1033 bytes (có thể dùng `c` để chỉ định đơn vị là bytes) 

Do hint là ***file có kích thước 1033***.

