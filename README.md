# Leetcode125
new_c = []
        for c in s:
            if c.isalnum():
                new_c.append(c.lower())
        length = len(new_c)
        for i in range(0,length/2):
            if new_c[i] != new_c[length-i-1]:
                return False
        return True
