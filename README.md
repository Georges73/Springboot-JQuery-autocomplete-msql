# Georges73-Sp-boot-JQuery-autocomplete-msql

This app demonstrates autocomplete search and displays the found data with it's proprties on the front-end. 


1. Create your DB and data in Mysql:

--
-- Table structure for table `product`
--

CREATE TABLE `product` (
  `id` int(11) NOT NULL,
  `name` varchar(250) NOT NULL,
  `price` decimal(10,1) NOT NULL,
  `quantity` int(11) NOT NULL,
  `description` text NOT NULL,
  `status` tinyint(1) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8 COLLATE=utf8_unicode_ci;

--
-- Dumping data for table `product`
--

INSERT INTO `product` (`name`, `price`, `quantity`, `description`, `status`) VALUES('Mobile 1', '1.0', 5, 'description 2', 1);
INSERT INTO `product` (`name`, `price`, `quantity`, `description`, `status`) VALUES('Mobile 2', '2.0', 2, 'description 1', 1);
INSERT INTO `product` (`name`, `price`, `quantity`, `description`, `status`) VALUES('Mobile 3', '11.0', 9, 'description 3', 1);
INSERT INTO `product` (`name`, `price`, `quantity`, `description`, `status`) VALUES('Laptop 4', '2.0', 15, 'description 9', 1);
INSERT INTO `product` (`name`, `price`, `quantity`, `description`, `status`) VALUES('Computer 1', '16.0', 8, 'description 7', 0);
INSERT INTO `product` (`name`, `price`, `quantity`, `description`, `status`) VALUES('Laptop 1', '22.0', 8, 'description 7', 0);
INSERT INTO `product` (`name`, `price`, `quantity`, `description`, `status`) VALUES('Laptop 2', '4.0', 11, 'description 8', 0);
INSERT INTO `product` (`name`, `price`, `quantity`, `description`, `status`) VALUES('Laptop 3', '9.0', 15, 'description 9', 1);
INSERT INTO `product` (`name`, `price`, `quantity`, `description`, `status`) VALUES('Computer 2', '3.0', 8, 'description 7', 0);


