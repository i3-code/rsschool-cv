## Igor Zakharov

### Contacts
- __Email__: [i3pobox@gmail.com](mailto:i3pobox@gmail.com)
- __Discord__: [urop9lxa#2659](discord:urop9lxa#2659)
- __Telegram__: [@i3play](https://t.me/i3play)

### Summary
My main aim is to study and get a good job as a front-end developer. It's my dream. I spend a lot of time on programming and learning English and I hope it'll help me.

### Skills
Perl, Lua, Python, a bit of SQL...

### Code samples
```python
#Spiral matrix filling
matrixShape = int(input())
matrix = [[0 for j in range(matrixShape)] for i in range(matrixShape)]
posX = 0
posY = -1
direction = 'right'
righRange = matrixShape - 1
downRange = matrixShape - 1
leftRange = 0
upRange = 1
for i in range(1, matrixShape * matrixShape + 1):
    if direction == 'right':
        posY += 1
        if posY > righRange:
            posY = righRange
            direction = 'down'
            righRange -= 1
    if direction == 'down':
        posX += 1
        if posX > downRange:
            posX = downRange
            direction = 'left'
            downRange -= 1
    if direction == 'left':
        posY -= 1
        if posY < leftRange:
            posY = leftRange
            direction = 'up'
            leftRange += 1
    if direction == 'up':
        posX -= 1
        if posX <= upRange:
            posX = upRange
            direction = 'right'
            upRange += 1
    matrix[posX][posY] = i
result = ''
for i in range(0, len(matrix)):
    resultLine = ''
    for j in range(0, len(matrix[i])):
        resultLine += str(matrix[i][j]) + '\t'
    result += resultLine[:-1] + '\n'
print(result)
```
### Education
High School

### English
A2+ according to the results of the last test. I'm still learning.