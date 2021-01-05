1.如何多次复制一个字符串
const laughing = '小智'.repeat(3)
consol.log(laughing) // "小智小智小智"

const eightBits = '1'.repeat(8)
console.log(eightBits) // "11111111"

2. 如何填充一个字符串到指定的长度
// 在开头添加 "0"，直到字符串的长度为 8。
const eightBits = '001'.padStart(8, '0')
console.log(eightBits) // "00000001"

//在末尾添加“ *”，直到字符串的长度为5。
const anonymizedCode = "34".padEnd(5, "*")
console.log(anonymizedCode) // "34***"

3.如何将字符串拆分为字符数组
const word = 'apple'
const characters = [...word]
console.log(characters) // ["a", "p", "p", "l", "e"]

4.如何计算字符串中的字符
const word = "apple";
console.log(word.length) // 5

5.如何反转字符串中的字符
const word = "apple"
const reversedWord = [...word].reverse().join("")
console.log(reversedWord) // "elppa"

6. 如何将字符串中的第一个字母大写
let word = 'apply'

word = word[0].toUpperCase() + word.substr(1)

console.log(word) // "Apple"
