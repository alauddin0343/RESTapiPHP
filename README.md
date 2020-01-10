# RESTapiPHP
I have developed a very simple RESTful API operations using PHP which is working well.

After downloading this code create the below database and table on your mysql.

<code>
  
  CREATE TABLE `emp` (
  `id` int(11) NOT NULL,
  `first_name` varchar(50) NOT NULL,
  `last_name` varchar(50) NOT NULL,
  `email` varchar(100) NOT NULL,
  `created_on` datetime NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

--
-- Dumping data for table `emp`
--

INSERT INTO `emp` (`id`, `first_name`, `last_name`, `email`, `created_on`) VALUES
(1, 'Abc', 'Xyz', 'abc@gmail.com', '2020-01-07 00:00:00'),
(2, 'Klm', 'Opq', 'klm@gmail.com', '2020-01-07 00:00:00'),
(4, 'Alauddin', 'Ansari', 'alauddin@gmail.com', '2020-01-07 00:00:00');

ALTER TABLE `emp`
  ADD PRIMARY KEY (`id`);
  
  ALTER TABLE `emp`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=5;
COMMIT;


</code>
