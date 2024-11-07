<?php
// Replace with your Spoonacular API Key
$apiKey = 'e1aca5950c474d49b9e2880b7d24a376';

// Check if ingredients are set in the URL query
if (isset($_GET['ingredients'])) {
    $ingredients = urlencode($_GET['ingredients']);
    
    // Define the Spoonacular API endpoint for recipe search
    $apiUrl = "https://api.spoonacular.com/recipes/findByIngredients?ingredients=$ingredients&number=5&apiKey=$apiKey";
    
    // Make the API request
    $response = file_get_contents($apiUrl);
    $recipes = json_decode($response, true);
}
?>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Recipe Finder</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="icon" href="Logo/icon.png" type="image/png">
    <style>
        /* Ensure full height and flex display for footer positioning */
        html, body {
            height: 100%;
            margin: 0;
            display: flex;
            flex-direction: column;
        }
        
        .content {
            flex: 1;
        }

        .header { 
            background-image: url('https://images.unsplash.com/photo-1512621776951-a57141f2eefd'); 
            background-size: cover; 
            background-position: center; 
            color: white; 
            text-align: center; 
            padding: 80px 20px;
        }
        .header h1 { font-size: 3em; margin-bottom: 0.5em; }
        .header p { font-size: 1.2em; max-width: 700px; margin: 0 auto; }

        .search-section { padding: 40px 0; }
        .recipe-card { border: 1px solid #ddd; padding: 15px; margin-bottom: 20px; border-radius: 8px; background-color: #fff; }
        .recipe-card img { max-width: 100%; border-radius: 8px; }
        
        /* Footer styling */
        footer { background-color: #343a40; color: white; padding: 20px 0; text-align: center; }
        footer a { color: #ffffff; text-decoration: none; margin: 0 10px; }
        footer a:hover { text-decoration: underline; }
    </style>
</head>
<body>

    <div class="content">
        <!-- Header Section with Background Image -->
        <div class="header">
            <h1>Welcome to Recipe Finder</h1>
            <p>Find delicious recipes based on the ingredients you already have at home! Save time, reduce waste, and enjoy cooking with ease.</p>
        </div>

        <!-- Search Section -->
        <div class="container search-section">
            <h2 class="text-center mb-4">Search Recipes by Ingredients</h2>
            <form method="GET" action="" class="d-flex justify-content-center">
                <div class="mb-3 w-75">
                    <label for="ingredients" class="form-label">Enter ingredients (comma-separated):</label>
                    <input type="text" id="ingredients" name="ingredients" class="form-control" placeholder="e.g., chicken, tomatoes, basil" required>
                </div>
                <button type="submit" class="btn btn-primary ms-2">Search</button>
            </form>
        </div>

        <!-- Recipe Results Section -->
        <div class="container">
            <?php if (isset($recipes) && !empty($recipes)): ?>
                <h3 class="my-4">Recipes:</h3>
                <div class="row">
                    <?php foreach ($recipes as $recipe): ?>
                        <div class="col-md-4">
                            <div class="recipe-card">
                                <h4 class="text-center"><?php echo htmlspecialchars($recipe['title']); ?></h4>
                                <img src="<?php echo htmlspecialchars($recipe['image']); ?>" alt="Recipe Image" class="img-fluid">
                                <p><strong>Used Ingredients:</strong> <?php echo count($recipe['usedIngredients']); ?></p>
                                <p><strong>Missed Ingredients:</strong> <?php echo count($recipe['missedIngredients']); ?></p>
                                <a href="https://spoonacular.com/recipes/<?php echo urlencode($recipe['title']); ?>-<?php echo $recipe['id']; ?>" target="_blank" class="btn btn-outline-primary btn-sm d-block mt-3">View Full Recipe</a>
                            </div>
                        </div>
                    <?php endforeach; ?>
                </div>
            <?php elseif (isset($ingredients)): ?>
                <p class="text-danger text-center">No recipes found. Try different ingredients.</p>
            <?php endif; ?>
        </div>
    </div>

    <!-- Footer Section -->
    <footer>
        <p>&copy; <?php echo date("Y"); ?> Recipe Finder. All rights reserved.</p>
        <div>
            <a href="#">About Us</a> | <a href="#">Contact</a> | <a href="#">Privacy Policy</a>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
