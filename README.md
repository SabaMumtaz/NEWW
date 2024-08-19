
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css"/>
<body>
    <section id="menu">
        <div class="logo">
            <img src="images/of.jpg">
            <h2>Online Food Store</h2>
        </div>
        <div class="items">
            <li><i class="fas fa-home"></i> <a  href="index.php">Categories</a></li>
            <li><i class="fab fa-first-order"></i><a  href="order.php">Order Detail</a></li>
            <li><i class="fas fa-address-card"></i><a  href="user_order.php">User Order Page</a></li>
            <li><i class="fab fa-product-hunt"></i><a  href="product.php">Product Types</a></li>
            <li><i class="fas fa-history"></i><a  href="user.php">User Detail</a></li>
            <li><i class="fas fa-address-card"></i><a  href="contact_us.php">Contact us</a></li>
            <li><i class="fas fa-minus-circle"></i> <a  href="#faq">FAQ</a></li>
            <li><i class="fas fa-power-off"></i> <a  href="logout.php">Logout</a></li>
        </div>
    </section>
    <section id="interface">
        <div class="navigation">
        <div class="n1">
            <div>
                <i id="menu-bt"class="fas fa-bars"></i>
            </div>
            <div class="search">
                <i class="fas fa-search"></i>
                <input type="text" placeholder="Search">
                

            </div>
        </div>
        <div class="profile">
            <i class="far fa-bell"></i>
            <img src="images/pic.jpg" class="img-fluid">
        </div>
        </div>  
        <h3 class="i-name">Dashboard</h3>
        <div class="values">
            <div class="val-box">
                <i class="fas fa-users"></i>
                <div>
                    <h3>8,267</h3>
                    <span>New Users</span>
                </div>
            </div>
            <div class="val-box">
                <i class="fas fa-shopping-cart"></i>
                <div>
                    <h3>8,267</h3>
                    <span>Total Orders</span>
                </div>
            </div>
            <div class="val-box">
                <i class="fas fa-dollar-sign"></i>
                <div>
                    <h3>215,542</h3>
                    <span>Product Sell</span>
                </div>
            </div>
            <div class="val-box">
                <i class="fas fa-dollar-sign"></i>
                <div>
                    <h3>215,542</h3>
                    <span>Product Sell</span>
                </div>
            </div>
        </div> 
        <div class="board">
            <table width="100%">
                <thead>
                    <tr>
                    <td>Name</td>
                    <td>Title</td>
                    <td>Status</td>
                    <td>Role</td>
                    <td>Role</td>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td class="people">
                            <img src="images/book.jpg"class="img-fluid">
                            <div class="people-de">
                                <h5>john Does</h5>
                                <p>john@example.com</p>
                            </div>
                        </td>
                        <td><h5>Software Engineer</h5>
                        <p>web dev</p></td>
                        <td><div class="active">
                            <p>Active</p></div></td>
                        <td>Owner</td>
                        <td><a href="#" class="btn">Edit</a></td>
                    </tr>
                </tbody>
                <tbody>
                    <tr>
                        <td class="people">
                            <img src="images/pic.jpg"class="img-fluid">
                            <div class="people-de">
                                <h5>john Does</h5>
                                <p>john@example.com</p>
                            </div>
                        </td>
                        <td><h5>Software Engineer</h5>
                        <p>web dev</p></td>
                        <td><div class="active">
                            <p>Active</p></div></td>
                        <td>Owner</td>
                        <td><a href="#" class="btn">Edit</a></td>
                    </tr>
                </tbody>
                <tbody>
                    <tr>
                        <td class="people">
                            <img src="images/1.jpg"class="img-fluid">
                            <div class="people-de">
                                <h5>john Does</h5>
                                <p>test@gmail.co.uk</p>
                            </div>
                        </td>
                        <td><h5>Software Engineer</h5>
                        <p>web dev</p></td>
                        <td><div class="active">
                            <p>Active</p></div></td>
                        <td>Owner</td>
                        <td><a href="#" class="btn">Edit</a></td>
                    </tr>
                </tbody>
                <tbody>
                    <tr>
                        <td class="people">
                            <img src="images/6.jpg"class="img-fluid">
                            <div class="people-de">
                                <h5>john Does</h5>
                                <p>fiza@example.com</p>
                            </div>
                        </td>
                        <td><h5>Software Engineer</h5>
                        <p>web dev</p></td>
                        <td><div class="active">
                            <p>Active</p></div></td>
                        <td>Owner</td>
                        <td><a href="#" class="btn">Edit</a></td>
                    </tr>
                </tbody>
            </table>
        </div> 
    </section>
    <script>
        $('#menu-bt').click(function(){
            $('#menu').toggleClass("active");
        });
    </script>
    
</body>
</html>
