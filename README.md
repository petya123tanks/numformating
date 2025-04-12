# Formatting Numbers

from sam_lie

Compatible with Lua 5.0 and 5.1.

# Example usage:


amount = 1333444.1

print(format_num(amount,2))

print(format_num(amount,-2,"US$"))



amount = -22333444.5634

print(format_num(amount,2,"$"))

print(format_num(amount,2,"$","()"))

print(format_num(amount,3,"$","NEG "))

# Output:

1,333,444.10

US$1,333,400

-$22,333,444.56

($22,333,444.56)

NEG $22,333,444.563
