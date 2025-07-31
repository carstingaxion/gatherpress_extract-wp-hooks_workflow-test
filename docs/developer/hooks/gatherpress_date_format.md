## Auto-generated Example

```php
add_filter(
   'gatherpress_date_format',
    function( $get_value ) {
        // Your code here.
        return $get_value;
    }
);
```

## Parameters

- `$get_value`

## Files

- [includes/core/classes/class-event.php:109](https://github.com/GatherPress/gatherpress/blob/develop/includes/core/classes/class-event.php#L109)
```php
apply_filters( 'gatherpress_date_format', $settings->get_value( 'general', 'formatting', 'date_format' ) )
```



[← All Hooks](Hooks)
