def write_name_to_file(name):
    filename = f"{name}.txt"
    with open(filename, "w") as f:
        f.write(name)

write_name_to_file("Your Name")

