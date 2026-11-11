## Code reference

```csharp
Console.WriteLine();
Console.ReadLine();
string textValue = “example text”
string upperCaseCopy = textValue.ToUpper();
string lowerCaseCopy = textValue.ToLower();
string composedPhrase = $”This contains {textValue}”;
string[] newStringArray = textValue.Split(“ “);
string firstWordInArray = newStringArray[0];
```

With “asking” and “returning” in the text below is assumed reading and writing to the Console. 

## 1
Ask the user to enter the name of a music instrument, accept their response and write the response to the Console in the format listed below. See the following input and output:

“Violin” => “Can you play the violin?”
“PIANO” => “Can you play the piano?”

## 2
Ask the user to enter their family name and accept their response. Then ask the user to enter their first name and accept that response too. Write the response to the Console in the format listed below. See the following input and output:

“Larsson”, “Peter” => “PETER LARSSON joined the firm”
“gratz”, “eva” => “EVA GRATZ joined the firm”

## 3
Ask the user to enter both their first name and family name in one single entry  and accept their response. Write the response to the Console in the format listed below. See the following input and output:

“Viveca Lawson” => “LAWSON, viveca : present”
“Hans Lorentz” => “LORENTZ, hans : present”


## Code reference

```csharp
string choice = Console.ReadLine();
If(choice == “bird”) {
	…
} else if (choice == “insect”) {
	…
} else {
	…
};
bool canVote = age ≥ 18;
char singleCharacter = ‘b’;
choice.Length
choice.EndsWith()
choice.StartsWith()
choice.Contains(“example”)
choice.Split(‘ ‘).Length
```

With “asking” and “returning” in the text below is assumed reading and writing to the Console. 

## 1
Ask the user if they have a gluten intolerance. Require them to answer with a “Yes” or a “No”. If the answer is “Yes”, respond with “You will be served gluten free food”. For “No”, answer “The regular menu will apply”. In all other cases, respond with “Unable to decide preference”.

## 2
Ask the user to enter some text. Treat as suspicious any text that contains the text snippet “drop database”. If the text contains such a snippet, respond with the message “Error 103: unable to process”.

## 3
Ask the user to go through a sign up for some unnamed service. Ask the user to enter a password and then an e-mail. Afterwards, inform the user if the password is not seven characters or longer that is must be so. Inform the user that the only accepted e-mail addresses must be of .se or .com kind. If both entries are correct, inform user that an account has been created. 

## 4
Ask the user to enter a sentence with at least seven words in it. Check that the text entered has at least seven words. If the check fails, return a message of “Not a correct sentence”, otherwise return a message of “Sentence accepted”.

## 5
Ask the user to enter their name. Respond with the message that begins with “Welcome” and then you repeat their name. But in case the name entered begins with “Lord”, like in “Lord Acton”, respond with “Welcome Your Excellency”.

## Code reference

```csharp
for(int i = 0; i < 7; i++) 
{
	…
};
for(int i = 0; i < exampleArray.Length; I++) { … }
int exampleNumber = 78;
++		// increment with 1
- -		// decrement with 1
5 % 2		// result will be 1 – what remains after division
```

With “asking” and “returning” in the text below is assumed reading and writing to the Console. 

## 1
An organisation is closing its accounts with a bank. The bank representative should return the total amount (write the number to the Console) based on this array of accounts balances: [5506, 291, 500, 482, 963]

## 2
Ask the user to enter some text. Then return the text entered, but in a format where every second word is uppercase and lowercase, like in this example: THIS was THE text ENTERED 

## 3
Ask the user to enter some text. Then return the text entered, but in a format where every word longer than six letters are succeeded with a text in parenthesis telling that it’s a long word: I have come to the conclusion (long word) that I must visit 

## 4
Ask the user to enter some text. Return each word in the text on its own line, but repeated the same amount of times as the letter length of the word. So a word of two letters will be repeated once, three letters twice (and one letter will not repeated at all). See this example: You You You will will will will adore adore adore adore adore us, us, us, I promise promise promise promise promise promise promise
