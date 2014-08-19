import sys

# Write a program to find the first non repeated character in a string.
def main():
    with open(sys.argv[1]) as file:
        for line in file:
            for i, character in enumerate(line):
                if character not in line[i+1:] and character not in line[0:i]:
                    print character
                    break

if __name__=="__main__": main()
