## Auto-generated Example

```php
add_filter(
   'gatherpress_time_format',
    function( $get_value ) {
        // Your code here.
        return $get_value;
    }
);
```

## Parameters

- `$get_value`

## Files

- [includes/core/classes/class-event.php:110](https://github.com/carstingaxion/gatherpress_extract-wp-hooks_workflow-test/blob/main/includes/core/classes/class-event.php#L110)
```php
apply_filters( 'gatherpress_time_format', $settings->get_value( 'general', 'formatting', 'time_format' ) )
```



[← All Hooks](Hooks)
