a. Multiple print() Statements
print("All the world's a stage,")
print("And all the men and women merely players:")
print("They have their exits and their entrances;")
print("And one man in his time plays many parts,")
print("His acts being seven ages.")
b. Single print() Statement
print("""All the world's a stage,
And all the men and women merely players:
They have their exits and their entrances;
And one man in his time plays many parts,
His acts being seven ages.""")
c. Predict the Output

The output will be:

127.0.0.1
d. Using flush=True and flush=False

flush=True can be used when you need the output to appear immediately. For example, it can be useful for a countdown or a program that shows live information.

flush=False is the default and allows Python to wait before sending the output. This is normally fine when you don't need the output to appear immediately.

Example:

print("Loading...", flush=True)
e. Understanding flush

The end argument can make print() output behave like flush=True when it is set to an empty string or another value that does not include a newline.

For example:

print("Loading...", end="", flush=True)

The flush=True argument is what directly tells Python to flush the output immediately.
