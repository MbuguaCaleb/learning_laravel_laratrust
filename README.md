**Running Role Seeder**

```
important files

(a)seeders---->DatabaseSeeder

Where i instantiated my laratrust seeder.

$this->call(LaratrustSeeder::class);

(b)Config----->Laratrust Seeder

Here is where i have my roles tied with the various relevant
permissions

(c)Role User

Any created user goes to role user.

It is the most important table and in my view works
with the session so as to know the authenticated  user...

Roles have permissions

Once i assing a role to a user, i polputate this
table..

On login this is the table that tells my session which
user type i am...


```
