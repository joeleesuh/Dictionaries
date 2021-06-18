def main():
    print('hello world')
    ages = {
        'Oprah': 67,
        'William': 38,
        'Kate': 39,
        'Harry': 36,
        'Meghan': 39,
        'Adele': 33,
        'JLaw': 30,
        'Rihanna': 33,
        'Obama': 59,
    }
    reversed_dict = reverse(ages)

    # standard code to print out a dictionary
    print('Reversed:')
    # for each key
    for key in reversed_dict:
        # print out the key, and its corresponding value.
        print(key, '->', reversed_dict[key])

def reverse(original):
    """
    should create and return a new dictionary where
    the values of the original are now keys!
    """
    reversed_dict = {}
    for old_key in original:
        old_value = original[old_key]

        # actually we need to make a list for every value
        if old_value not in reversed_dict:
            # if it is the first time you have seen old_value...
            reversed_dict[old_value] = [old_key]
        else:
            # otherwise, find the list that already exists...
            reversed_dict[old_value].append(old_key)
    return reversed_dict

if __name__ == '__main__':
    main()
