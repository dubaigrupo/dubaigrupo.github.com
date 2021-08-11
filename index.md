<?php
/**
 * Grupo 04
 * Grupo 03
 * Grupo 05
 * Grupo 06
 */

$addresses = [
	'https://chat.whatsapp.com/D4cfK2lkDN14ihwMglnDqt',
	
	
	
];

$size = count($addresses);
$randomIndex = rand(0, $size - 1);
$randomUrl = $addresses[$randomIndex];

header('Location: ' . $randomUrl, true, 303);

?>
