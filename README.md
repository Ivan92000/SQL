-- phpMyAdmin SQL Dump
-- version 5.2.0
-- https://www.phpmyadmin.net/
--
-- Hôte : 127.0.0.1:3306
-- Généré le : mer. 12 avr. 2023 à 20:05
-- Version du serveur : 8.0.31
-- Version de PHP : 8.0.26

SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
START TRANSACTION;
SET time_zone = "+00:00";


/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!40101 SET NAMES utf8mb4 */;

--
-- Base de données : `sqlquests`
--

-- --------------------------------------------------------

--
-- Structure de la table `employee`
--

DROP TABLE IF EXISTS `employee`;
CREATE TABLE IF NOT EXISTS `employee` (
  `id` int NOT NULL AUTO_INCREMENT,
  `lastname` varchar(50) DEFAULT NULL,
  `firstname` varchar(50) DEFAULT NULL,
  `email` varchar(250) DEFAULT NULL,
  `date_system` timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP,
  PRIMARY KEY (`id`)
) ENGINE=MyISAM AUTO_INCREMENT=33 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;

--
-- Déchargement des données de la table `employee`
--

INSERT INTO `employee` (`id`, `lastname`, `firstname`, `email`, `date_system`) VALUES
(1, 'Ramirez', 'Violet', 'Violet.Ramirez@videnupu.pk', '2023-04-12 19:16:20'),
(2, 'Mannucci', 'Carlos', 'Carlos.Mannucci@wahahja.pn', '2023-04-12 19:16:20'),
(3, 'Ikeda', 'Susan', 'Susan.Ikeda@so.ac', '2023-04-12 19:18:41'),
(4, 'McGuire', 'Sean', 'Sean.McGuire@fut.td', '2023-04-12 19:18:41'),
(5, 'Cavicchi', 'Jon', 'Jon.Cavicchi@zan.pg', '2023-04-12 19:20:05'),
(6, 'Verbeek', 'Peter', 'Peter.Verbeek@onefiba.rs', '2023-04-12 19:20:05'),
(7, 'Wong', 'Todd', 'Todd.Wong@fe.hu', '2023-04-12 19:21:17'),
(8, 'Watson', 'Alice', 'Alice.Watson@jazus.cr', '2023-04-12 19:21:17'),
(9, 'Ciabatti', 'Millie', 'Millie.Ciabatti@faotori.qa', '2023-04-12 19:22:45'),
(10, 'Marino', 'Alejandro', 'Alejandro.Marino@uvhimvi.si', '2023-04-12 19:22:45'),
(11, 'Patterson', 'Maud', 'Maud.Patterson@dawmevgeb.gt', '2023-04-12 19:24:13'),
(12, 'Diez', 'Andre', 'Andre.Diez@isiavra.km', '2023-04-12 19:24:13'),
(13, 'Dean', 'Jackson', 'Jackson.Dean@atjon.cc', '2023-04-12 19:24:48'),
(14, 'Bernardi', 'Barbara', 'Barbara.Bernardi@kegavbag.kz', '2023-04-12 19:25:27'),
(15, 'Valk', 'Cameron', 'Cameron.Valk@pa.bo', '2023-04-12 19:26:36'),
(16, 'van Oosten', 'Calvin', 'Calvin.van Oosten@ekidafij.ps', '2023-04-12 19:26:36'),
(17, 'Mazzei', 'Ollie', 'Ollie.Mazzei@ze.ag', '2023-04-12 19:27:17'),
(18, 'Blake', 'Jack', 'Jack.Blake@kur.ru', '2023-04-12 19:47:45'),
(19, 'Tran', 'Edwin', 'Edwin.Tran@rezi.pf', '2023-04-12 19:47:45'),
(20, 'Butler', 'Celia', 'Celia.Butler@hilcehbi.tw', '2023-04-12 19:49:15'),
(21, 'Bouvier', 'Adele', 'Adele.Bouvier@ta.bg', '2023-04-12 19:49:15'),
(22, 'Amato', 'Dylan', 'Dylan.Amato@ukihom.gy', '2023-04-12 19:50:39'),
(23, 'Black', 'Louisa', 'Louisa.Black@bemufe.bs', '2023-04-12 19:50:39'),
(24, 'Ndiaye', 'Lloyd', 'Lloyd.Ndiaye@wilcu.cw', '2023-04-12 19:51:55'),
(25, 'Carrai', 'Mattie', 'Mattie.Carrai@ipe.bo', '2023-04-12 19:51:55'),
(26, 'van der Heijden', 'Stephen', 'Stephen.van der Heijden@fu.eh', '2023-04-12 19:53:02'),
(27, 'Rodgers', 'Ollie', 'Ollie.Rodgers@ufa.io', '2023-04-12 19:53:02'),
(28, 'Cantini', 'Brent', 'Brent.Cantini@wunpa.am', '2023-04-12 19:54:07'),
(29, 'Michel', 'Ricardo', 'Ricardo.Michel@do.tp', '2023-04-12 19:54:07'),
(30, 'Hunt', 'Gabriel', 'Gabriel.Hunt@ha.com', '2023-04-12 19:55:11'),
(31, 'Sanz', 'Chris', 'Chris.Sanz@ju.tn', '2023-04-12 19:55:11'),
(32, 'Guerrero', 'Cora', 'Cora.Guerrero@zuwovho.wf', '2023-04-12 19:55:46');
COMMIT;

/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
/*!40101 SET CHARACTER_SET_RESULTS=@OLD_CHARACTER_SET_RESULTS */;
/*!40101 SET COLLATION_CONNECTION=@OLD_COLLATION_CONNECTION */;
