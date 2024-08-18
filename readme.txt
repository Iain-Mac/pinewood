note1:will fire up on https://localhost:7100/Customers
note2: if we use a real database, eg sql server get get certificate authority errors due to the self-signed certificate
note3: so any changes; insert,deletes,edits will not persist across instances
note4: two nuget packages are required to run

	dotnet add package Microsoft.EntityFrameworkCore
	dotnet add package Microsoft.EntityFrameworkCore.InMemory

