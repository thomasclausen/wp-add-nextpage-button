# Description

Simple functionality plugin that adds the "Next page" button to TinyMCE in WordPress.

REMEMBER to use the "wp_link_pages()" function to display the links.

# Examples

Currently no examples...

# Usage

The code to insert looks like this:

    <?php $args = array( 'before' => '<p>Pages: ', 'after' => '</p>', 'next_or_number' => 'next_and_number', 'previouspagelink' => 'Previous', 'nextpagelink' => 'Next' );
	wp_link_pages( $args ); ?>

options:

    'next_or_number' => 'next_and_number' - choices: 'number', 'next' or 'next_and_number'