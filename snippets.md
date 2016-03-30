# Install Drupal Console
```
# Run this in your terminal to get the latest project version:
curl https://drupalconsole.com/installer -L -o drupal.phar

# Accessing from anywhere on your system:
mv drupal.phar /usr/local/bin/drupal

# Apply executable permissions on the downloaded file:
chmod +x /usr/local/bin/drupal

# Check and validate system requirements
drupal check

# Copy configuration files to user home directory:
drupal init --override
```

# Download Drupal
```
drupal site:new drupal8.dev 8.0.5
```

# Change directory
```
cd drupal8.dev/
```

# Install Drupal
```
drupal site:install
```

# Generate module
```
drupal generate:module
```

# Debug module list
```
drupal module:debug | grep example
```

# Install module
```
drupal module:install example
```

# Generate controller
```
drupal generate:controller
```

# Generate Configuration Form
```
drupal generate:form:config
```

# Generate Plugin Block
```
drupal generate:plugin:block  --module="example" --class="ExampleBlock" --label="example_block" --plugin-id="example_block" --theme-region="sidebar_second"
```
# Generate Content Entity
```
drupal generate:entity:content --module="example" --entity-class="Foo" --entity-name="foo" --no-interaction
```



