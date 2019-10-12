def encrypt(message):

    Encrypted_Message = ""
    message = "".join(message.split())
    for i in range(0, len(message)):

        c = ord(message[i]) - 64
        Encrypted_Message += str(c) + " "
    return (Encrypted_Message)


def decrypt(message):

    Decrypted_Message = ""
    message = message.split()

    for c in message:
        c = chr(int(c) + 64)
        Decrypted_Message += c
    return (Decrypted_Message)


print('<---Please select one of the options given below--->\nNOTE: Do not forget to use capital letters only And I am so sorry about the space issue :)')
Value = int(input('1 : Encryption\n2 : Decryption\n-->'))


if(Value == 1):
    Message = input("Please Enter Your MESSAGE (Plain Text) : ")
    print("Encrypted Message : ", encrypt(Message))


elif(Value == 2):
    Message = input("Please Enter Your MESSAGE (Cipher Text) : ")
    print("Decrypted Message : ", decrypt(Message))

else:
    print('Please Select the Valid Option')
