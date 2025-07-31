# projet
projet de groupe
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="services.css.css">
    <title>services</title>
</head>
<body>
    <div>
        <div>
            <div>
                <h1>Welcome to our educational services</h1>
                <p>Here we provide to our students up to date leasons</p>
                    <div>
                        <label for="subject" class="block text-sm font-medium text-gray-700 mb-1">Select your Educational section</label>
                        <select id="subject" name="subject" class="w-full px-4 py-3 rounded-lg border border-gray-300 focus:border-indigo-500 form-input transition duration-150 ease-in-out">
                            <option value="">Select a section</option>
                            <option value="English">Anglophone</option>
                            <option value="French">Francophone</option>
                        </select>
                        <p id="languagError" class="error-message"></p>
                    </div>
                    <div>
                        <label for="subject" class="block text-sm font-medium text-gray-700 mb-1">Select your class level</label>
                        <select id="subject" name="subject" class="w-full px-4 py-3 rounded-lg border border-gray-300 focus:border-indigo-500 form-input transition duration-150 ease-in-out">
                            <option value="">Select your level</option>
                            <option value="6 ème">6 ème</option>
                            <option value="5 ème">5 ème</option>
                            <option value="4 ème">4 ème</option>
                            <option value="3 ème">3 ème</option>
                            <option value="2 nd">2 nd</option>
                        </select>
                        <p id="levelError" class="error-message"></p>
                    </div>
                    <div>
                        <label for="subject" class="block text-sm font-medium text-gray-700 mb-1">Select a subject</label>
                        <select id="subject" name="subject" class="w-full px-4 py-3 rounded-lg border border-gray-300 focus:border-indigo-500 form-input transition duration-150 ease-in-out">
                            <option value="">Select a subject</option>
                            <option value="Mathématiques">Mathématiques</option>
                            <option value="Anglais">Anglais</option>
                            <option value="Physique">Physique</option>
                            <option value="Chimie">Chimie</option>
                            <option value="Informatique">Informatique</option>
                        </select>
                        <p id="levelError" class="error-message"></p>
                    </div>
                <button>Start leasons</button>
            </div>
        </div>
        
    </div>
</body>
</html>
