Nano-Placeholder
================

Pico Plugin for handling placeholder images.

### Installation

Start by moving the <code>plugins/nano_placeholder.php</code> file into your existing Pico install. Then define the placeholder attributes in the configuration array. You can override the <code>default</code> attributes or define custom styles.

### Configuration

	$config["nano_placeholder"] = array(
		"default" => array(
			"background_color" => "CCCCCC",
			"text_color" => "666666",
			"image" => false,
			"text" => false
		),
		"custom" => array(
			"background_color" => "222222",
			"text_color" => "666666",
			"image" => false,
			"text" => "Placeholder"
		)
	);

### Usage

You can then start requesting placeholder images:

	http://site.com/placeholder/300x300

<img src="http://formstone.it/placeholder/300x200" />

	http://site.com/placeholder/custom/300x300

<img src="http://formstone.it/placeholder/custom/300x200" />