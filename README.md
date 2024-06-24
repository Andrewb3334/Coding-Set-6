# Coding-Set-6
def main():
    filename = "my_name.txt"
    name = "Andrew Block"

    try:
        with open(filename, 'w') as file:
            file.write(name + "\n")
        print(f"Successfully wrote {name} to {filename}")
    except I0Error:
        print(f"Error: Could not write to {filename}")

if __name__ == "__main__":
    main()
def main():
   

    try: 

      with open(filename, 'r') as file:

          name = file.readline().strip()
      
      print(f"The name read from {filename} is: {name}")
      

if __name__ == "__main__":
    main()
