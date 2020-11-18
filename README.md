
  # Clone the repository 
  git clone https://github.com/Eliot8/KONECT

  # Move in the folder
  cd KONECT

  # Install the dependencies
  composer install

  # Install the asset package
  composer require asset

  # Start the server
  php -S localhost:8000 -t public
