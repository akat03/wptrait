# Laravel Wordpress wpautop Trait

## Usage

### Step 1: Copy WpTrait.php in your /app


### Step 2: Use Trait

```
class Mymodel extends Model
{
	use WpTrait;    
}

```

### Step 3: Use wpautop() in Laravel Blade View

```
	{!! $mymodel->wpautop($mymodel->contents)  !!}
```

