import random
import string

def generate_password(length):
    characters = string.ascii_letters + string.digits + string.punctuation
    password = ''.join(random.choice(characters) for _ in range(length))
    return password

# Example usage: Generate a 12-character password
password = generate_password(12)
print('Password is this - {}'.format(password))# password-generator-project-in-python
