## 1
From the code below, break out the code snippet into a separate method and call this method at the same point where the code used  to be. Make the code work as before.

Snippet:
```csharp
password.ToLower() == "pencil"
```

Code:

```csharp
Console.WriteLine("Enter your password:");
string password = Console.ReadLine();

bool passwordMatch = password.ToLower() == "pencil";

if (passwordMatch)
{
    Console.WriteLine("Success");
}
else
{
    Console.WriteLine("Login failed");
}
```

## 2
From the code below, break out the code snippet into a separate method and call this method at the same point where the code used  to be. Make the code work as before.

Snippet:
```csharp
for (int i = 0; i < users.Length; i++)
{
    if (users[i][0] == username.ToLower())
    {
        userMatch = i;
    }
}
```

Code:

```csharp
string[][] users = [["john", "plate"], ["michelle", "bike"], ["lisa", "pencil"]];
Console.WriteLine("Enter your username:");
string username = Console.ReadLine();
Console.WriteLine("Enter your password:");
string password = Console.ReadLine();
int userMatch = -1;
for (int i = 0; i < users.Length; i++)
{
    if (users[i][0] == username.ToLower())
    {
        userMatch = i;
    }
}
bool passwordMatch = false;
if (userMatch > -1)
{
    passwordMatch = password.ToLower() == users[userMatch][1];
}
if (passwordMatch)
{
    Console.WriteLine("Success");
}
else
{
    Console.WriteLine("Login failed");
}
```

## 3 
From the code below, break out the three separate code snippets into separate methods and call these methods at the same point where the code used  to be. Make the code work as before. 

Snippet 1:
```csharp
Console.WriteLine("Enter your username:");
string username = Console.ReadLine();
Console.WriteLine("Enter your password:");
string password = Console.ReadLine();
```

Snippet 2:
```csharp
int userMatch = -1;
for (int i = 0; i < users.Length; i++)
{
    if (users[i][0] == username.ToLower())
    {
        userMatch = i;
    }
}
bool passwordMatch = false;
if (userMatch > -1)
{
    passwordMatch = password.ToLower() == users[userMatch][1];
}
```

Snippet 3:
```csharp
if (passwordMatch)
{
    Console.WriteLine("Success");
}
else
{
    Console.WriteLine("Login failed");
}
```

Code:

```csharp
string[][] users = [["john", "plate"], ["michelle", "bike"], ["lisa", "pencil"]];
Console.WriteLine("Enter your username:");
string username = Console.ReadLine();
Console.WriteLine("Enter your password:");
string password = Console.ReadLine();
int userMatch = -1;
for (int i = 0; i < users.Length; i++)
{
    if (users[i][0] == username.ToLower())
    {
        userMatch = i;
    }
}
bool passwordMatch = false;
if (userMatch > -1)
{
    passwordMatch = password.ToLower() == users[userMatch][1];
}
if (passwordMatch)
{
    Console.WriteLine("Success");
}
else
{
    Console.WriteLine("Login failed");
}

```

## 4
Write a method that takes a string array and returns the length of the longest string in the array. 

## 5
Write a method that takes three int values, adds the first two numbers together, then compares the sum with the third number and if the sum is bigger than the third number, returns true, otherwise false. 