<?php

$value = "madam";

$reverse = strrev($value);

echo "Given Value: " . $value . "<br>";

if ($value == $reverse) {
    echo "It is a Palindrome";
} else {
    echo "It is not a Palindrome";
}

?>
Given Value: madam
It is a Palindrome
