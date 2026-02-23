-- phpMyAdmin SQL Dump
-- version 5.2.1
-- https://www.phpmyadmin.net/
--
-- Host: 127.0.0.1
-- Generation Time: Feb 23, 2026 at 09:12 AM
-- Server version: 10.4.32-MariaDB
-- PHP Version: 8.2.12

SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
START TRANSACTION;
SET time_zone = "+00:00";


/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!40101 SET NAMES utf8mb4 */;

--
-- Database: `storylens`
--

-- --------------------------------------------------------

--
-- Table structure for table `article`
--

CREATE TABLE `article` (
  `art_id` int(11) NOT NULL,
  `title` varchar(254) DEFAULT NULL,
  `summary` varchar(1000) DEFAULT NULL,
  `content` text DEFAULT NULL,
  `created` timestamp NOT NULL DEFAULT current_timestamp() ON UPDATE current_timestamp(),
  `category_id` int(11) DEFAULT NULL,
  `member_id` int(11) DEFAULT NULL,
  `image_id` int(11) DEFAULT NULL,
  `published` tinyint(1) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Dumping data for table `article`
--

INSERT INTO `article` (`art_id`, `title`, `summary`, `content`, `created`, `category_id`, `member_id`, `image_id`, `published`) VALUES
(1, 'Urban Harvest Poster', 'Poster design for community event', 'This poster was created to promote an annual urban farming festival. The design uses bold typography and vibrant green tones to emphasize sustainability and community involvement.', '2026-02-23 07:25:55', 1, 1, 1, 1),
(2, 'Code Conference Website', 'Website design for tech event', 'A responsive website designed for a global coding conference. The interface focuses on clarity and usability while incorporating animated transitions to reflect innovation.', '2021-05-02 06:22:11', 2, 2, 2, 1),
(3, 'Mountain Adventure', 'Illustration for travel blog', 'A detailed digital illustration created for a travel blog feature about hiking destinations. The artwork combines textured brushes and layered lighting to create depth and atmosphere.', '2021-05-03 01:45:27', 3, 3, 3, 1),
(4, 'Morning Light', 'Landscape photography series', 'Part of a photography series capturing early morning light across coastal cliffs. Shot using natural light to enhance the soft pastel tones of sunrise.', '2021-05-03 22:30:44', 4, 1, 4, 1),
(5, 'Minimal Business Cards', 'Corporate stationery design', 'A clean and modern business card set designed for a financial consultancy. The layout uses generous white space and subtle embossing for a premium feel.', '2021-05-05 03:05:18', 1, 2, 5, 1),
(6, 'Fitness Tracker App', 'Mobile app interface design', 'An intuitive app interface for tracking workouts and health data. The design prioritizes accessibility, bold icons, and simplified navigation patterns.', '2021-05-06 07:42:33', 2, 3, 6, 1),
(7, 'City Park Mural', 'Illustration for public art project', 'A large-scale mural illustration celebrating diversity within the community. The artwork features flowing shapes and vibrant colors to attract engagement.', '2021-05-07 05:20:59', 3, 1, 7, 1),
(8, 'Desert Textures', 'Editorial photography', 'A close-up photographic study of desert sand formations. Macro techniques were used to capture intricate wind-sculpted patterns.', '2021-05-08 09:55:41', 4, 2, 8, 1),
(9, 'Art Expo Catalogue', 'Catalogue design for exhibition', 'A printed exhibition catalogue showcasing contemporary artists. The design uses a structured grid layout and muted tones to let the artwork stand out.', '2021-05-09 04:33:12', 1, 3, 9, 1),
(10, 'E-Learning Platform', 'Educational website design', 'A digital learning platform designed for remote students. The interface emphasizes readability, structured modules, and integrated video lessons.', '2021-05-10 08:48:25', 2, 1, 10, 1),
(11, 'Children’s Book Artwork', 'Illustrations for storybook', 'Whimsical illustrations created for a children’s fantasy book. The characters were designed with soft lines and expressive features to engage young readers.', '2021-05-11 02:10:10', 3, 2, 11, 1),
(12, 'Industrial Portraits', 'Black and white photography series', 'A portrait series capturing factory workers in industrial settings. Shot in monochrome to emphasize texture and character.', '2021-05-12 10:22:49', 4, 3, 12, 1),
(13, 'Eco Packaging Design', 'Sustainable packaging project', 'A packaging solution developed for an organic skincare brand. Recycled materials and minimalist typography reinforce the environmental ethos.', '2021-05-13 01:14:36', 1, 1, 13, 1),
(14, 'Restaurant Booking App', 'UX/UI design for hospitality', 'A mobile booking app designed for a restaurant chain. The design integrates smooth reservation flows and rich food imagery.', '2021-05-14 12:01:15', 2, 2, 14, 1),
(15, 'Space Explorer', 'Sci-fi themed illustration', 'A futuristic illustration depicting astronauts exploring distant planets. Neon highlights and dramatic shadows create a cinematic effect.', '2021-05-15 06:27:53', 3, 3, 15, 1),
(16, 'Forest Trail', 'Nature photography project', 'A photography project documenting forest trails during autumn. Warm tones and natural framing guide the viewer through each composition.', '2021-05-15 23:39:28', 4, 1, 16, 1),
(17, 'Luxury Brochure', 'High-end real estate brochure', 'A printed brochure showcasing luxury apartments. The design combines elegant serif typography with full-bleed photography.', '2021-05-17 03:55:44', 1, 2, 17, 1),
(18, 'Music Streaming UI', 'Interface design for streaming service', 'A clean and immersive streaming interface allowing users to discover playlists and artists seamlessly across devices.', '2021-05-18 08:12:09', 2, 3, 18, 1),
(19, 'Wildlife Characters', 'Illustration series for campaign', 'A playful set of animal illustrations created for an environmental awareness campaign. Each character was designed to communicate a specific conservation message.', '2021-05-19 05:41:57', 3, 1, 19, 1),
(20, 'City Nights', 'Urban night photography', 'A photography series capturing the reflections and neon glow of city streets after dark. Long exposure techniques highlight motion and light trails.', '2021-05-20 13:18:22', 4, 2, 20, 1),
(21, 'Festival Flyer', 'Print design for summer festival', 'A vibrant flyer designed to promote a summer arts festival. Bright gradients and layered typography create a sense of excitement.', '2021-05-21 02:05:31', 1, 3, 21, 1),
(22, 'Travel Agency Website', 'Responsive website redesign', 'A full website redesign for a travel agency focusing on destination imagery and simplified booking systems.', '2021-05-22 07:36:48', 2, 1, 22, 1),
(23, 'Fashion Sketch Series', 'Editorial fashion illustrations', 'A series of expressive fashion sketches created for a seasonal editorial. Loose brush strokes and bold silhouettes define the aesthetic.', '2021-05-23 04:22:17', 3, 2, 23, 1),
(24, 'Ocean Waves', 'Seascape photography', 'A seascape photograph capturing powerful waves under dramatic skies. A slow shutter speed was used to soften the motion of the water.', '2021-05-24 11:44:55', 4, 3, 24, 1);

-- --------------------------------------------------------

--
-- Table structure for table `category`
--

CREATE TABLE `category` (
  `cat_id` int(11) NOT NULL,
  `name` varchar(24) DEFAULT NULL,
  `description` varchar(254) DEFAULT NULL,
  `navigation` tinyint(1) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Dumping data for table `category`
--

INSERT INTO `category` (`cat_id`, `name`, `description`, `navigation`) VALUES
(1, 'Print', 'Inspiring graphic design', 1),
(2, 'Digital', 'Powerful pixels', 1),
(3, 'Illustration', 'Hand-drawn visual storytelling', 1),
(4, 'Photography', 'Capturing the moment', 1);

-- --------------------------------------------------------

--
-- Table structure for table `image`
--

CREATE TABLE `image` (
  `img_id` int(11) NOT NULL,
  `file` varchar(254) DEFAULT NULL,
  `alt` varchar(1000) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

-- --------------------------------------------------------

--
-- Table structure for table `member`
--

CREATE TABLE `member` (
  `mem_id` int(11) NOT NULL,
  `forename` varchar(254) DEFAULT NULL,
  `surname` varchar(254) DEFAULT NULL,
  `email` varchar(254) DEFAULT NULL,
  `password` varchar(254) DEFAULT NULL,
  `joined` timestamp NOT NULL DEFAULT current_timestamp() ON UPDATE current_timestamp(),
  `picture` varchar(254) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Dumping data for table `member`
--

INSERT INTO `member` (`mem_id`, `forename`, `surname`, `email`, `password`, `joined`, `picture`) VALUES
(1, 'Emi', 'Klinnium', 'emi@eg.link', 'c63j-82ve-2sv9-qlb38', '2021-04-25 04:04:23', 'emi.jpg'),
(2, 'Bonnie', 'Pattraphus', 'boni@eg.link', 'saq8-2f2k-3nv7-fa4k', '2021-01-27 04:15:18', 'bonnie.jpg'),
(3, 'Ciize', 'Rutricha', 'cii@eg.link', 'sk3r-vd92-3vn1-exm2', '2021-09-23 02:53:47', 'ciize.jpg');

--
-- Indexes for dumped tables
--

--
-- Indexes for table `article`
--
ALTER TABLE `article`
  ADD PRIMARY KEY (`art_id`);

--
-- Indexes for table `category`
--
ALTER TABLE `category`
  ADD PRIMARY KEY (`cat_id`);

--
-- Indexes for table `image`
--
ALTER TABLE `image`
  ADD PRIMARY KEY (`img_id`);

--
-- Indexes for table `member`
--
ALTER TABLE `member`
  ADD PRIMARY KEY (`mem_id`);
COMMIT;

/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
/*!40101 SET CHARACTER_SET_RESULTS=@OLD_CHARACTER_SET_RESULTS */;
/*!40101 SET COLLATION_CONNECTION=@OLD_COLLATION_CONNECTION */;
