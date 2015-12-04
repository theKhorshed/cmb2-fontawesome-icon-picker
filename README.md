CMB2 Field Type: Font-Awesome Picker
==================

Custom field for [CMB2](https://github.com/WebDevStudios/CMB2).

##Example

```php
// Classic CMB2 declaration
$cmb = new_cmb2_box( array(
  'id'           => 'prefix-metabox-id',
  'title'        => __( 'Title', 'textdomain' ),
  'object_types' => array( 'post', ), // Post type
) );

// Add new field
$cmb->add_field( array(
  'name'        => __( 'Select Icon', 'textdomain' ),
  'id'          => 'prefix_icon',
  'type'        => 'fontawesome_icon', // This field type
) );
```

### Credits ###
This plugin uses the following jquery plugin

[https://github.com/mjolnic/fontawesome-iconpicker](https://github.com/mjolnic/fontawesome-iconpicker)
