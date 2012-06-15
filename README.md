# Description

Simple functionality plugin that adds the "Next page" button to TinyMCE in WordPress.

REMEMBER to use the "wp_link_pages()" function to display the links.

# Examples

Currently no examples...

# Usage

Download it, upload it and activate it!

The code to insert looks like this:

    <?php $args = array( 'before' => '<p>Pages: ', 'after' => '</p>', 'next_or_number' => 'next_and_number', 'previouspagelink' => 'Previous', 'nextpagelink' => 'Next' );
	wp_link_pages( $args ); ?>

options:

    'next_or_number' => 'next_and_number' - choices: 'number', 'next' or 'next_and_number'

# Feedback

I'm self-taught by scattering code across the web, so if you see some bad practices PLEASE contact me, so I can learn from the mistakes I'm making!

Also feel free to contact me if you have som great ideas for improvements.

# License

Credits would be nice, but feel free to use as often as you like.