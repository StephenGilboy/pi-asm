# pi-asm
Go just isn't metal enough. Time to learn ARM Assembly. 


## Assembling
### Assemble the source code:

`as -o outObject1.s sourceCode.s`

`as -o outObject2.s sourceCode2.s`

### Link the objects

`ld -o finalProgram outObject1.s outObject2.s`

## Commands
* MOV - MOVe data 
* SWI - Call the Raspbian OS
* BAL - Brach ALways: Branch to another source file. See `part1.s` & `part2.s`