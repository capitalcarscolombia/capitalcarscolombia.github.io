# <!DOCTYPE html>

# <html lang="es">

# <head>

# &nbsp;   <meta charset="UTF-8">

# &nbsp;   <meta name="viewport" content="width=device-width, initial-scale=1.0">

# &nbsp;   <title>Capital Cars S.A.S - Compra y Venta de Vehículos Premium en Colombia</title>

# &nbsp;   <meta name="description" content="Capital Cars S.A.S - Especialistas en compra y venta de vehículos premium. Vehículos certificados, financiación y el mejor servicio en Colombia.">

# &nbsp;   <meta name="keywords" content="carros, venta de vehículos, compra de carros, financiación, Capital Cars, Bogotá, Colombia">

# &nbsp;   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

# &nbsp;   <style>

# &nbsp;       :root {

# &nbsp;           --primary: #1a365d;

# &nbsp;           --secondary: #2d5b8a;

# &nbsp;           --accent: #c53030;

# &nbsp;           --light: #f7fafc;

# &nbsp;           --dark: #2d3748;

# &nbsp;           --gray: #718096;

# &nbsp;           --light-gray: #e2e8f0;

# &nbsp;           --gold: #ffc107;

# &nbsp;       }

# &nbsp;       

# &nbsp;       \* {

# &nbsp;           margin: 0;

# &nbsp;           padding: 0;

# &nbsp;           box-sizing: border-box;

# &nbsp;           font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;

# &nbsp;       }

# &nbsp;       

# &nbsp;       body {

# &nbsp;           background-color: #ffffff;

# &nbsp;           color: var(--dark);

# &nbsp;           line-height: 1.6;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .container {

# &nbsp;           max-width: 1200px;

# &nbsp;           margin: 0 auto;

# &nbsp;           padding: 0 20px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       /\* Header \*/

# &nbsp;       header {

# &nbsp;           background-color: white;

# &nbsp;           box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);

# &nbsp;           position: sticky;

# &nbsp;           top: 0;

# &nbsp;           z-index: 100;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .header-content {

# &nbsp;           display: flex;

# &nbsp;           justify-content: space-between;

# &nbsp;           align-items: center;

# &nbsp;           padding: 15px 0;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .logo {

# &nbsp;           font-size: 28px;

# &nbsp;           font-weight: 700;

# &nbsp;           color: var(--primary);

# &nbsp;           display: flex;

# &nbsp;           align-items: center;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .logo i {

# &nbsp;           margin-right: 10px;

# &nbsp;           color: var(--accent);

# &nbsp;       }

# &nbsp;       

# &nbsp;       nav ul {

# &nbsp;           display: flex;

# &nbsp;           list-style: none;

# &nbsp;       }

# &nbsp;       

# &nbsp;       nav ul li {

# &nbsp;           margin-left: 30px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       nav ul li a {

# &nbsp;           text-decoration: none;

# &nbsp;           color: var(--dark);

# &nbsp;           font-weight: 500;

# &nbsp;           transition: color 0.3s;

# &nbsp;           position: relative;

# &nbsp;       }

# &nbsp;       

# &nbsp;       nav ul li a:hover {

# &nbsp;           color: var(--secondary);

# &nbsp;       }

# &nbsp;       

# &nbsp;       nav ul li a.active {

# &nbsp;           color: var(--secondary);

# &nbsp;       }

# &nbsp;       

# &nbsp;       nav ul li a.active::after {

# &nbsp;           content: '';

# &nbsp;           position: absolute;

# &nbsp;           bottom: -5px;

# &nbsp;           left: 0;

# &nbsp;           width: 100%;

# &nbsp;           height: 2px;

# &nbsp;           background-color: var(--secondary);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .hero {

# &nbsp;           background: linear-gradient(rgba(26, 54, 93, 0.85), rgba(26, 54, 93, 0.9)), url('https://images.unsplash.com/photo-1494976388531-d1058494cdd8?ixlib=rb-4.0.3\&auto=format\&fit=crop\&w=1200\&q=80');

# &nbsp;           background-size: cover;

# &nbsp;           background-position: center;

# &nbsp;           color: white;

# &nbsp;           padding: 100px 0;

# &nbsp;           text-align: center;

# &nbsp;           margin-bottom: 60px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .hero h1 {

# &nbsp;           font-size: 48px;

# &nbsp;           margin-bottom: 20px;

# &nbsp;           font-weight: 700;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .hero p {

# &nbsp;           font-size: 20px;

# &nbsp;           max-width: 700px;

# &nbsp;           margin: 0 auto 30px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .btn {

# &nbsp;           display: inline-block;

# &nbsp;           padding: 14px 30px;

# &nbsp;           background-color: var(--accent);

# &nbsp;           color: white;

# &nbsp;           border: none;

# &nbsp;           border-radius: 4px;

# &nbsp;           cursor: pointer;

# &nbsp;           font-size: 16px;

# &nbsp;           font-weight: 600;

# &nbsp;           transition: all 0.3s;

# &nbsp;           text-decoration: none;

# &nbsp;           text-align: center;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .btn:hover {

# &nbsp;           background-color: #9c2525;

# &nbsp;           transform: translateY(-2px);

# &nbsp;           box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .btn-outline {

# &nbsp;           background-color: transparent;

# &nbsp;           border: 2px solid white;

# &nbsp;           margin-left: 15px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .btn-outline:hover {

# &nbsp;           background-color: white;

# &nbsp;           color: var(--primary);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .section-title {

# &nbsp;           font-size: 32px;

# &nbsp;           color: var(--primary);

# &nbsp;           margin-bottom: 40px;

# &nbsp;           text-align: center;

# &nbsp;           position: relative;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .section-title::after {

# &nbsp;           content: '';

# &nbsp;           position: absolute;

# &nbsp;           bottom: -10px;

# &nbsp;           left: 50%;

# &nbsp;           transform: translateX(-50%);

# &nbsp;           width: 80px;

# &nbsp;           height: 3px;

# &nbsp;           background-color: var(--accent);

# &nbsp;       }

# &nbsp;       

# &nbsp;       /\* Vehículos \*/

# &nbsp;       .vehicles-section {

# &nbsp;           padding: 80px 0;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .vehicles-grid {

# &nbsp;           display: grid;

# &nbsp;           grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));

# &nbsp;           gap: 30px;

# &nbsp;           margin-top: 40px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .vehicle-card {

# &nbsp;           background: white;

# &nbsp;           border-radius: 8px;

# &nbsp;           overflow: hidden;

# &nbsp;           box-shadow: 0 5px 15px rgba(0, 0, 0, 0.08);

# &nbsp;           transition: transform 0.3s, box-shadow 0.3s;

# &nbsp;           border: 1px solid var(--light-gray);

# &nbsp;           position: relative;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .vehicle-card:hover {

# &nbsp;           transform: translateY(-10px);

# &nbsp;           box-shadow: 0 15px 30px rgba(0, 0, 0, 0.15);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .vehicle-image {

# &nbsp;           height: 220px;

# &nbsp;           overflow: hidden;

# &nbsp;           position: relative;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .vehicle-image img {

# &nbsp;           width: 100%;

# &nbsp;           height: 100%;

# &nbsp;           object-fit: cover;

# &nbsp;           transition: transform 0.5s;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .vehicle-card:hover .vehicle-image img {

# &nbsp;           transform: scale(1.05);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .sold-badge {

# &nbsp;           position: absolute;

# &nbsp;           top: 15px;

# &nbsp;           right: 15px;

# &nbsp;           background-color: var(--accent);

# &nbsp;           color: white;

# &nbsp;           padding: 8px 15px;

# &nbsp;           border-radius: 4px;

# &nbsp;           font-weight: bold;

# &nbsp;           font-size: 14px;

# &nbsp;           z-index: 2;

# &nbsp;           box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .sold-overlay {

# &nbsp;           position: absolute;

# &nbsp;           top: 0;

# &nbsp;           left: 0;

# &nbsp;           width: 100%;

# &nbsp;           height: 100%;

# &nbsp;           background-color: rgba(0, 0, 0, 0.6);

# &nbsp;           display: flex;

# &nbsp;           align-items: center;

# &nbsp;           justify-content: center;

# &nbsp;           z-index: 1;

# &nbsp;           opacity: 0;

# &nbsp;           transition: opacity 0.3s;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .vehicle-card.sold .sold-overlay {

# &nbsp;           opacity: 1;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .sold-text {

# &nbsp;           color: white;

# &nbsp;           font-size: 24px;

# &nbsp;           font-weight: bold;

# &nbsp;           text-transform: uppercase;

# &nbsp;           transform: rotate(-15deg);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .vehicle-card.sold {

# &nbsp;           opacity: 0.8;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .vehicle-card.sold:hover {

# &nbsp;           transform: none;

# &nbsp;           box-shadow: 0 5px 15px rgba(0, 0, 0, 0.08);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .vehicle-details {

# &nbsp;           padding: 25px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .vehicle-title {

# &nbsp;           font-size: 20px;

# &nbsp;           font-weight: 600;

# &nbsp;           margin-bottom: 10px;

# &nbsp;           color: var(--primary);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .vehicle-info {

# &nbsp;           margin-bottom: 20px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .vehicle-info-item {

# &nbsp;           display: flex;

# &nbsp;           justify-content: space-between;

# &nbsp;           margin-bottom: 8px;

# &nbsp;           font-size: 14px;

# &nbsp;           color: var(--gray);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .vehicle-price {

# &nbsp;           font-size: 24px;

# &nbsp;           font-weight: 700;

# &nbsp;           color: var(--accent);

# &nbsp;           margin: 20px 0;

# &nbsp;           text-align: center;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .vehicle-actions {

# &nbsp;           display: flex;

# &nbsp;           gap: 10px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .vehicle-actions .btn {

# &nbsp;           flex: 1;

# &nbsp;           padding: 12px;

# &nbsp;           font-size: 14px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .btn-whatsapp {

# &nbsp;           background-color: #25D366;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .btn-whatsapp:hover {

# &nbsp;           background-color: #128C7E;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .btn-secondary {

# &nbsp;           background-color: var(--secondary);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .btn-secondary:hover {

# &nbsp;           background-color: #1e4a8a;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .btn-description {

# &nbsp;           background-color: var(--primary);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .btn-description:hover {

# &nbsp;           background-color: #0f2547;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .btn-disabled {

# &nbsp;           background-color: var(--gray);

# &nbsp;           cursor: not-allowed;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .btn-disabled:hover {

# &nbsp;           background-color: var(--gray);

# &nbsp;           transform: none;

# &nbsp;           box-shadow: none;

# &nbsp;       }

# &nbsp;       

# &nbsp;       /\* Filtros \*/

# &nbsp;       .filters-container {

# &nbsp;           background-color: var(--light);

# &nbsp;           padding: 20px;

# &nbsp;           border-radius: 8px;

# &nbsp;           margin-bottom: 30px;

# &nbsp;           box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .filter-title {

# &nbsp;           font-size: 18px;

# &nbsp;           font-weight: 600;

# &nbsp;           margin-bottom: 15px;

# &nbsp;           color: var(--primary);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .filters-grid {

# &nbsp;           display: grid;

# &nbsp;           grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));

# &nbsp;           gap: 15px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .filter-group {

# &nbsp;           margin-bottom: 10px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .filter-group label {

# &nbsp;           display: block;

# &nbsp;           margin-bottom: 5px;

# &nbsp;           font-weight: 500;

# &nbsp;           color: var(--dark);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .filter-select, .filter-input {

# &nbsp;           width: 100%;

# &nbsp;           padding: 10px;

# &nbsp;           border: 1px solid var(--light-gray);

# &nbsp;           border-radius: 4px;

# &nbsp;           font-size: 14px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .filter-actions {

# &nbsp;           display: flex;

# &nbsp;           gap: 10px;

# &nbsp;           margin-top: 10px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .filter-actions .btn {

# &nbsp;           flex: 1;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .btn-clear {

# &nbsp;           background-color: var(--gray);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .btn-clear:hover {

# &nbsp;           background-color: #5a6268;

# &nbsp;       }

# &nbsp;       

# &nbsp;       /\* Modal \*/

# &nbsp;       .modal {

# &nbsp;           display: none;

# &nbsp;           position: fixed;

# &nbsp;           top: 0;

# &nbsp;           left: 0;

# &nbsp;           width: 100%;

# &nbsp;           height: 100%;

# &nbsp;           background-color: rgba(0, 0, 0, 0.7);

# &nbsp;           z-index: 1000;

# &nbsp;           overflow-y: auto;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .modal-content {

# &nbsp;           background-color: white;

# &nbsp;           margin: 5% auto;

# &nbsp;           padding: 30px;

# &nbsp;           border-radius: 8px;

# &nbsp;           width: 90%;

# &nbsp;           max-width: 800px;

# &nbsp;           position: relative;

# &nbsp;           box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .close-modal {

# &nbsp;           position: absolute;

# &nbsp;           top: 15px;

# &nbsp;           right: 20px;

# &nbsp;           font-size: 28px;

# &nbsp;           font-weight: bold;

# &nbsp;           color: var(--gray);

# &nbsp;           cursor: pointer;

# &nbsp;           transition: color 0.3s;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .close-modal:hover {

# &nbsp;           color: var(--accent);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .modal-header {

# &nbsp;           margin-bottom: 20px;

# &nbsp;           border-bottom: 1px solid var(--light-gray);

# &nbsp;           padding-bottom: 15px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .modal-title {

# &nbsp;           font-size: 24px;

# &nbsp;           color: var(--primary);

# &nbsp;           margin-bottom: 5px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .modal-subtitle {

# &nbsp;           color: var(--gray);

# &nbsp;           font-size: 16px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .modal-body {

# &nbsp;           margin-bottom: 20px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .modal-image {

# &nbsp;           width: 100%;

# &nbsp;           height: 300px;

# &nbsp;           object-fit: cover;

# &nbsp;           border-radius: 8px;

# &nbsp;           margin-bottom: 20px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .features-list {

# &nbsp;           display: grid;

# &nbsp;           grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));

# &nbsp;           gap: 10px;

# &nbsp;           margin-top: 20px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .feature-item {

# &nbsp;           display: flex;

# &nbsp;           align-items: center;

# &nbsp;           margin-bottom: 10px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .feature-item i {

# &nbsp;           color: var(--secondary);

# &nbsp;           margin-right: 10px;

# &nbsp;           width: 20px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       /\* Sección Vender \*/

# &nbsp;       .sell-section {

# &nbsp;           padding: 80px 0;

# &nbsp;           background-color: var(--light);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .sell-steps {

# &nbsp;           display: grid;

# &nbsp;           grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));

# &nbsp;           gap: 30px;

# &nbsp;           margin-bottom: 50px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .step-card {

# &nbsp;           background: white;

# &nbsp;           padding: 30px;

# &nbsp;           border-radius: 8px;

# &nbsp;           text-align: center;

# &nbsp;           box-shadow: 0 5px 15px rgba(0, 0, 0, 0.08);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .step-icon {

# &nbsp;           width: 70px;

# &nbsp;           height: 70px;

# &nbsp;           background: var(--primary);

# &nbsp;           color: white;

# &nbsp;           border-radius: 50%;

# &nbsp;           display: flex;

# &nbsp;           align-items: center;

# &nbsp;           justify-content: center;

# &nbsp;           margin: 0 auto 20px;

# &nbsp;           font-size: 30px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .step-title {

# &nbsp;           font-size: 20px;

# &nbsp;           margin-bottom: 15px;

# &nbsp;           color: var(--primary);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .step-description {

# &nbsp;           color: var(--gray);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .form-container {

# &nbsp;           max-width: 800px;

# &nbsp;           margin: 0 auto;

# &nbsp;           background: white;

# &nbsp;           padding: 40px;

# &nbsp;           border-radius: 8px;

# &nbsp;           box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .form-group {

# &nbsp;           margin-bottom: 20px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .form-group label {

# &nbsp;           display: block;

# &nbsp;           margin-bottom: 8px;

# &nbsp;           font-weight: 500;

# &nbsp;           color: var(--dark);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .form-control {

# &nbsp;           width: 100%;

# &nbsp;           padding: 12px 15px;

# &nbsp;           border: 1px solid var(--light-gray);

# &nbsp;           border-radius: 4px;

# &nbsp;           font-size: 16px;

# &nbsp;           transition: border-color 0.3s;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .form-control:focus {

# &nbsp;           border-color: var(--secondary);

# &nbsp;           outline: none;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .form-row {

# &nbsp;           display: flex;

# &nbsp;           gap: 20px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .form-row .form-group {

# &nbsp;           flex: 1;

# &nbsp;       }

# &nbsp;       

# &nbsp;       /\* Financiación \*/

# &nbsp;       .finance-section {

# &nbsp;           padding: 80px 0;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .finance-calculator {

# &nbsp;           background: white;

# &nbsp;           border-radius: 8px;

# &nbsp;           box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);

# &nbsp;           overflow: hidden;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .calculator-container {

# &nbsp;           display: flex;

# &nbsp;           flex-wrap: wrap;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .calculator-inputs {

# &nbsp;           flex: 1;

# &nbsp;           min-width: 300px;

# &nbsp;           padding: 30px;

# &nbsp;           background-color: var(--light);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .calculator-results {

# &nbsp;           flex: 1;

# &nbsp;           min-width: 300px;

# &nbsp;           padding: 30px;

# &nbsp;           background-color: var(--primary);

# &nbsp;           color: white;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .calculator-results h3 {

# &nbsp;           margin-bottom: 20px;

# &nbsp;           font-size: 24px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .result-item {

# &nbsp;           display: flex;

# &nbsp;           justify-content: space-between;

# &nbsp;           margin-bottom: 15px;

# &nbsp;           padding-bottom: 15px;

# &nbsp;           border-bottom: 1px solid rgba(255, 255, 255, 0.2);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .result-value {

# &nbsp;           font-weight: 700;

# &nbsp;           font-size: 18px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .calculator-notice {

# &nbsp;           background-color: rgba(255, 255, 255, 0.1);

# &nbsp;           padding: 15px;

# &nbsp;           border-radius: 4px;

# &nbsp;           margin-top: 20px;

# &nbsp;           font-size: 14px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       /\* Contacto \*/

# &nbsp;       .contact-section {

# &nbsp;           padding: 80px 0;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .contact-grid {

# &nbsp;           display: grid;

# &nbsp;           grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));

# &nbsp;           gap: 30px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .contact-info {

# &nbsp;           background: var(--light);

# &nbsp;           padding: 30px;

# &nbsp;           border-radius: 8px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .contact-info h3 {

# &nbsp;           margin-bottom: 20px;

# &nbsp;           color: var(--primary);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .contact-item {

# &nbsp;           display: flex;

# &nbsp;           align-items: flex-start;

# &nbsp;           margin-bottom: 20px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .contact-item i {

# &nbsp;           margin-right: 15px;

# &nbsp;           color: var(--secondary);

# &nbsp;           font-size: 20px;

# &nbsp;           margin-top: 5px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       /\* Autorización de datos \*/

# &nbsp;       .authorization-container {

# &nbsp;           background-color: var(--light);

# &nbsp;           border-radius: 8px;

# &nbsp;           padding: 20px;

# &nbsp;           margin: 20px 0;

# &nbsp;           border-left: 4px solid var(--secondary);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .authorization-text {

# &nbsp;           font-size: 14px;

# &nbsp;           color: var(--dark);

# &nbsp;           margin-bottom: 15px;

# &nbsp;           line-height: 1.5;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .authorization-buttons {

# &nbsp;           display: flex;

# &nbsp;           gap: 15px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .authorization-buttons .btn {

# &nbsp;           flex: 1;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .btn-success {

# &nbsp;           background-color: #28a745;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .btn-success:hover {

# &nbsp;           background-color: #218838;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .btn-danger {

# &nbsp;           background-color: #dc3545;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .btn-danger:hover {

# &nbsp;           background-color: #c82333;

# &nbsp;       }

# &nbsp;       

# &nbsp;       /\* Footer \*/

# &nbsp;       footer {

# &nbsp;           background-color: var(--primary);

# &nbsp;           color: white;

# &nbsp;           padding: 60px 0 30px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .footer-content {

# &nbsp;           display: grid;

# &nbsp;           grid-template-columns: repeat(4, 1fr);

# &nbsp;           gap: 40px;

# &nbsp;           margin-bottom: 40px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .footer-section h3 {

# &nbsp;           margin-bottom: 20px;

# &nbsp;           font-size: 18px;

# &nbsp;           position: relative;

# &nbsp;           padding-bottom: 10px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .footer-section h3::after {

# &nbsp;           content: '';

# &nbsp;           position: absolute;

# &nbsp;           bottom: 0;

# &nbsp;           left: 0;

# &nbsp;           width: 40px;

# &nbsp;           height: 2px;

# &nbsp;           background-color: var(--accent);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .footer-section p {

# &nbsp;           margin-bottom: 10px;

# &nbsp;           font-size: 14px;

# &nbsp;           color: rgba(255, 255, 255, 0.8);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .footer-section i {

# &nbsp;           margin-right: 10px;

# &nbsp;           width: 20px;

# &nbsp;           text-align: center;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .copyright {

# &nbsp;           text-align: center;

# &nbsp;           padding-top: 30px;

# &nbsp;           border-top: 1px solid rgba(255, 255, 255, 0.1);

# &nbsp;           font-size: 14px;

# &nbsp;           color: rgba(255, 255, 255, 0.7);

# &nbsp;       }

# &nbsp;       

# &nbsp;       /\* Responsive \*/

# &nbsp;       @media (max-width: 992px) {

# &nbsp;           .footer-content {

# &nbsp;               grid-template-columns: repeat(2, 1fr);

# &nbsp;           }

# &nbsp;       }

# &nbsp;       

# &nbsp;       @media (max-width: 768px) {

# &nbsp;           .header-content {

# &nbsp;               flex-direction: column;

# &nbsp;           }

# &nbsp;           

# &nbsp;           nav ul {

# &nbsp;               margin-top: 20px;

# &nbsp;           }

# &nbsp;           

# &nbsp;           nav ul li {

# &nbsp;               margin: 0 10px;

# &nbsp;           }

# &nbsp;           

# &nbsp;           .hero h1 {

# &nbsp;               font-size: 36px;

# &nbsp;           }

# &nbsp;           

# &nbsp;           .hero p {

# &nbsp;               font-size: 18px;

# &nbsp;           }

# &nbsp;           

# &nbsp;           .vehicles-grid {

# &nbsp;               grid-template-columns: 1fr;

# &nbsp;           }

# &nbsp;           

# &nbsp;           .footer-content {

# &nbsp;               grid-template-columns: 1fr;

# &nbsp;           }

# &nbsp;           

# &nbsp;           .form-row {

# &nbsp;               flex-direction: column;

# &nbsp;               gap: 0;

# &nbsp;           }

# &nbsp;           

# &nbsp;           .vehicle-actions {

# &nbsp;               flex-direction: column;

# &nbsp;           }

# &nbsp;           

# &nbsp;           .modal-content {

# &nbsp;               width: 95%;

# &nbsp;               margin: 10% auto;

# &nbsp;               padding: 20px;

# &nbsp;           }

# &nbsp;           

# &nbsp;           .authorization-buttons {

# &nbsp;               flex-direction: column;

# &nbsp;           }

# &nbsp;           

# &nbsp;           .filters-grid {

# &nbsp;               grid-template-columns: 1fr;

# &nbsp;           }

# &nbsp;           

# &nbsp;           .calculator-container {

# &nbsp;               flex-direction: column;

# &nbsp;           }

# &nbsp;       }

# 

# &nbsp;       .loading {

# &nbsp;           text-align: center;

# &nbsp;           padding: 20px;

# &nbsp;           color: var(--gray);

# &nbsp;       }

# &nbsp;       

# &nbsp;       /\* Estilos para validaciones \*/

# &nbsp;       .validation-message {

# &nbsp;           font-size: 14px;

# &nbsp;           margin-top: 5px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .validation-success {

# &nbsp;           color: #28a745;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .validation-error {

# &nbsp;           color: var(--accent);

# &nbsp;       }

# &nbsp;       

# &nbsp;       .input-valid {

# &nbsp;           border-color: #28a745 !important;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .input-invalid {

# &nbsp;           border-color: var(--accent) !important;

# &nbsp;       }

# &nbsp;       

# &nbsp;       /\* Estilos para el modal de confirmación \*/

# &nbsp;       .confirmation-modal {

# &nbsp;           display: none;

# &nbsp;           position: fixed;

# &nbsp;           top: 0;

# &nbsp;           left: 0;

# &nbsp;           width: 100%;

# &nbsp;           height: 100%;

# &nbsp;           background-color: rgba(0, 0, 0, 0.7);

# &nbsp;           z-index: 2000;

# &nbsp;           overflow-y: auto;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .confirmation-content {

# &nbsp;           background-color: white;

# &nbsp;           margin: 10% auto;

# &nbsp;           padding: 30px;

# &nbsp;           border-radius: 8px;

# &nbsp;           width: 90%;

# &nbsp;           max-width: 500px;

# &nbsp;           position: relative;

# &nbsp;           box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);

# &nbsp;           text-align: center;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .confirmation-icon {

# &nbsp;           font-size: 48px;

# &nbsp;           color: var(--accent);

# &nbsp;           margin-bottom: 20px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .confirmation-title {

# &nbsp;           font-size: 24px;

# &nbsp;           color: var(--primary);

# &nbsp;           margin-bottom: 15px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .confirmation-text {

# &nbsp;           color: var(--dark);

# &nbsp;           margin-bottom: 25px;

# &nbsp;           line-height: 1.6;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .confirmation-buttons {

# &nbsp;           display: flex;

# &nbsp;           gap: 15px;

# &nbsp;           justify-content: center;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .confirmation-buttons .btn {

# &nbsp;           min-width: 120px;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .btn-confirm {

# &nbsp;           background-color: #28a745;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .btn-confirm:hover {

# &nbsp;           background-color: #218838;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .btn-cancel {

# &nbsp;           background-color: #6c757d;

# &nbsp;       }

# &nbsp;       

# &nbsp;       .btn-cancel:hover {

# &nbsp;           background-color: #5a6268;

# &nbsp;       }

# &nbsp;   </style>

# </head>

# <body>

# &nbsp;   <header>

# &nbsp;       <div class="container">

# &nbsp;           <div class="header-content">

# &nbsp;               <div class="logo">

# &nbsp;                   <i class="fas fa-car"></i>

# &nbsp;                   Capital Cars S.A.S

# &nbsp;               </div>

# &nbsp;               <nav>

# &nbsp;                   <ul>

# &nbsp;                       <li><a href="#vehiculos" class="active">Vehículos</a></li>

# &nbsp;                       <li><a href="#vender">Vender</a></li>

# &nbsp;                       <li><a href="#financiacion">Financiación</a></li>

# &nbsp;                       <li><a href="#contacto">Contacto</a></li>

# &nbsp;                   </ul>

# &nbsp;               </nav>

# &nbsp;           </div>

# &nbsp;       </div>

# &nbsp;   </header>

# &nbsp;   

# &nbsp;   <section class="hero">

# &nbsp;       <div class="container">

# &nbsp;           <h1>Capital Cars S.A.S</h1>

# &nbsp;           <p>Tu socio de confianza para la compra y venta de vehículos premium</p>

# &nbsp;           <p style="margin-top: 15px; font-size: 18px;">

# &nbsp;               <i class="fas fa-handshake"></i> Aliados estratégicos de <strong>Dacar Autos</strong> para todo Colombia

# &nbsp;           </p>

# &nbsp;           <a href="#vehiculos" class="btn">Ver Vehículos</a>

# &nbsp;           <a href="#vender" class="btn btn-outline">Vender Mi Vehículo</a>

# &nbsp;       </div>

# &nbsp;   </section>

# &nbsp;   

# &nbsp;   <section id="vehiculos" class="vehicles-section">

# &nbsp;       <div class="container">

# &nbsp;           <h2 class="section-title">Vehículos Disponibles</h2>

# &nbsp;           <p style="text-align: center; max-width: 700px; margin: 0 auto 40px; color: var(--gray);">

# &nbsp;               Explora nuestra selección de vehículos cuidadosamente seleccionados. Todos han pasado por rigurosas inspecciones para garantizar su calidad.

# &nbsp;           </p>

# &nbsp;           

# &nbsp;           <!-- Filtros -->

# &nbsp;           <div class="filters-container">

# &nbsp;               <h3 class="filter-title">Filtrar Vehículos</h3>

# &nbsp;               <div class="filters-grid">

# &nbsp;                   <div class="filter-group">

# &nbsp;                       <label for="filterStatus">Estado</label>

# &nbsp;                       <select id="filterStatus" class="filter-select">

# &nbsp;                           <option value="all">Todos</option>

# &nbsp;                           <option value="available">Disponibles</option>

# &nbsp;                           <option value="sold">Vendidos</option>

# &nbsp;                       </select>

# &nbsp;                   </div>

# &nbsp;                   

# &nbsp;                   <div class="filter-group">

# &nbsp;                       <label for="filterPrice">Precio máximo</label>

# &nbsp;                       <select id="filterPrice" class="filter-select">

# &nbsp;                           <option value="all">Todos los precios</option>

# &nbsp;                           <option value="50000000">Hasta $50.000.000</option>

# &nbsp;                           <option value="80000000">Hasta $80.000.000</option>

# &nbsp;                           <option value="100000000">Hasta $100.000.000</option>

# &nbsp;                           <option value="150000000">Hasta $150.000.000</option>

# &nbsp;                       </select>

# &nbsp;                   </div>

# &nbsp;                   

# &nbsp;                   <div class="filter-group">

# &nbsp;                       <label for="filterYear">Año mínimo</label>

# &nbsp;                       <select id="filterYear" class="filter-select">

# &nbsp;                           <option value="all">Todos los años</option>

# &nbsp;                           <option value="2020">2020 o más nuevo</option>

# &nbsp;                           <option value="2018">2018 o más nuevo</option>

# &nbsp;                           <option value="2015">2015 o más nuevo</option>

# &nbsp;                           <option value="2010">2010 o más nuevo</option>

# &nbsp;                       </select>

# &nbsp;                   </div>

# &nbsp;                   

# &nbsp;                   <div class="filter-group">

# &nbsp;                       <label for="filterFuel">Combustible</label>

# &nbsp;                       <select id="filterFuel" class="filter-select">

# &nbsp;                           <option value="all">Todos</option>

# &nbsp;                           <option value="Gasolina">Gasolina</option>

# &nbsp;                           <option value="Híbrido">Híbrido</option>

# &nbsp;                       </select>

# &nbsp;                   </div>

# &nbsp;               </div>

# &nbsp;               

# &nbsp;               <div class="filter-actions">

# &nbsp;                   <button id="applyFilters" class="btn">Aplicar Filtros</button>

# &nbsp;                   <button id="clearFilters" class="btn btn-clear">Limpiar Filtros</button>

# &nbsp;               </div>

# &nbsp;           </div>

# &nbsp;           

# &nbsp;           <div class="vehicles-grid" id="vehiclesContainer">

# &nbsp;               <!-- Los vehículos se cargarán aquí con JavaScript -->

# &nbsp;           </div>

# &nbsp;       </div>

# &nbsp;   </section>

# &nbsp;   

# &nbsp;   <section id="vender" class="sell-section">

# &nbsp;       <div class="container">

# &nbsp;           <h2 class="section-title">Vende Tu Vehículo</h2>

# &nbsp;           <p style="text-align: center; max-width: 700px; margin: 0 auto 40px; color: var(--gray);">

# &nbsp;               Vende tu vehículo de forma rápida, segura y al mejor precio. Te ofrecemos una evaluación justa y transparente.

# &nbsp;           </p>

# &nbsp;           

# &nbsp;           <div class="sell-steps">

# &nbsp;               <div class="step-card">

# &nbsp;                   <div class="step-icon">

# &nbsp;                       <i class="fas fa-clipboard-list"></i>

# &nbsp;                   </div>

# &nbsp;                   <h3 class="step-title">Solicita una Evaluación</h3>

# &nbsp;                   <p class="step-description">Completa el formulario con los datos de tu vehículo para recibir una valoración inicial.</p>

# &nbsp;               </div>

# &nbsp;               

# &nbsp;               <div class="step-card">

# &nbsp;                   <div class="step-icon">

# &nbsp;                       <i class="fas fa-car"></i>

# &nbsp;                   </div>

# &nbsp;                   <h3 class="step-title">Inspección Técnica</h3>

# &nbsp;                   <p class="step-description">Nuestros expertos revisarán tu vehículo para confirmar su estado y valor real.</p>

# &nbsp;               </div>

# &nbsp;               

# &nbsp;               <div class="step-card">

# &nbsp;                   <div class="step-icon">

# &nbsp;                       <i class="fas fa-handshake"></i>

# &nbsp;                   </div>

# &nbsp;                   <h3 class="step-title">Oferta y Negociación</h3>

# &nbsp;                   <p class="step-description">Recibirás una oferta justa y transparente por tu vehículo.</p>

# &nbsp;               </div>

# &nbsp;               

# &nbsp;               <div class="step-card">

# &nbsp;                   <div class="step-icon">

# &nbsp;                       <i class="fas fa-money-bill-wave"></i>

# &nbsp;                   </div>

# &nbsp;                   <h3 class="step-title">Pago Inmediato</h3>

# &nbsp;                   <p class="step-description">Una vez aceptada la oferta, recibirás el pago de inmediato.</p>

# &nbsp;               </div>

# &nbsp;           </div>

# &nbsp;           

# &nbsp;           <div class="form-container">

# &nbsp;               <h3 style="text-align: center; margin-bottom: 30px; color: var(--primary);">Solicita una Valoración</h3>

# &nbsp;               <form id="sellForm">

# &nbsp;                   <div class="form-row">

# &nbsp;                       <div class="form-group">

# &nbsp;                           <label for="sellName">Nombre completo \*</label>

# &nbsp;                           <input type="text" id="sellName" class="form-control" required>

# &nbsp;                           <div id="sellNameValidation" class="validation-message"></div>

# &nbsp;                       </div>

# &nbsp;                       <div class="form-group">

# &nbsp;                           <label for="sellPhone">Teléfono \*</label>

# &nbsp;                           <input type="tel" id="sellPhone" class="form-control" required>

# &nbsp;                           <div id="sellPhoneValidation" class="validation-message"></div>

# &nbsp;                       </div>

# &nbsp;                   </div>

# &nbsp;                   

# &nbsp;                   <div class="form-group">

# &nbsp;                       <label for="sellEmail">Correo electrónico \*</label>

# &nbsp;                       <input type="email" id="sellEmail" class="form-control" required>

# &nbsp;                       <div id="sellEmailValidation" class="validation-message"></div>

# &nbsp;                   </div>

# &nbsp;                   

# &nbsp;                   <div class="form-row">

# &nbsp;                       <div class="form-group">

# &nbsp;                           <label for="vehicleBrand">Marca del vehículo \*</label>

# &nbsp;                           <input type="text" id="vehicleBrand" class="form-control" required>

# &nbsp;                       </div>

# &nbsp;                       <div class="form-group">

# &nbsp;                           <label for="vehicleModel">Modelo \*</label>

# &nbsp;                           <input type="text" id="vehicleModel" class="form-control" required>

# &nbsp;                       </div>

# &nbsp;                   </div>

# &nbsp;                   

# &nbsp;                   <div class="form-row">

# &nbsp;                       <div class="form-group">

# &nbsp;                           <label for="vehicleYear">Año \*</label>

# &nbsp;                           <input type="number" id="vehicleYear" class="form-control" min="1990" max="2025" required>

# &nbsp;                       </div>

# &nbsp;                       <div class="form-group">

# &nbsp;                           <label for="vehicleMileage">Kilometraje \*</label>

# &nbsp;                           <input type="number" id="vehicleMileage" class="form-control" min="0" required>

# &nbsp;                       </div>

# &nbsp;                   </div>

# &nbsp;                   

# &nbsp;                   <div class="form-group">

# &nbsp;                       <label for="additionalInfo">Información adicional</label>

# &nbsp;                       <textarea id="additionalInfo" class="form-control" rows="4" placeholder="Describe el estado general de tu vehículo, características especiales, etc."></textarea>

# &nbsp;                   </div>

# &nbsp;                   

# &nbsp;                   <!-- Autorización de datos -->

# &nbsp;                   <div class="authorization-container">

# &nbsp;                       <p class="authorization-text">

# &nbsp;                           <strong>AUTORIZACIÓN DE TRATAMIENTO DE DATOS PERSONALES</strong><br>

# &nbsp;                           De conformidad con la Ley 1581 de 2012 y el Decreto Reglamentario 1377 de 2013, autorizo de manera voluntaria, previa, explícita, informada e inequívoca a CAPITAL CARS S.A.S. para tratar mis datos personales con la finalidad de contactarme, realizar cotizaciones, prestar los servicios solicitados, enviar información comercial y realizar actividades de mercadeo relacionadas con nuestros productos y servicios. Conozco que puedo ejercer mis derechos de acceso, corrección, actualización, supresión y revocación del consentimiento a través del correo electrónico capitalcarscolombia@gmail.com.

# &nbsp;                       </p>

# &nbsp;                       <div class="authorization-buttons">

# &nbsp;                           <button type="button" id="sellAcceptBtn" class="btn btn-success">

# &nbsp;                               <i class="fas fa-check-circle"></i> Sí, autorizo

# &nbsp;                           </button>

# &nbsp;                           <button type="button" id="sellDeclineBtn" class="btn btn-danger">

# &nbsp;                               <i class="fas fa-times-circle"></i> No autorizo

# &nbsp;                           </button>

# &nbsp;                       </div>

# &nbsp;                   </div>

# &nbsp;                   

# &nbsp;                   <button type="submit" class="btn" style="width: 100%;" id="sellSubmitBtn" disabled>

# &nbsp;                       <i class="fab fa-whatsapp"></i> Enviar Solicitud por WhatsApp

# &nbsp;                   </button>

# &nbsp;               </form>

# &nbsp;           </div>

# &nbsp;       </div>

# &nbsp;   </section>

# &nbsp;   

# &nbsp;   <section id="financiacion" class="finance-section">

# &nbsp;       <div class="container">

# &nbsp;           <h2 class="section-title">Simulador de Financiación</h2>

# &nbsp;           <p style="text-align: center; max-width: 700px; margin: 0 auto 40px; color: var(--gray);">

# &nbsp;               Calcula tus cuotas mensuales y descubre el plan de financiación que mejor se adapte a tus necesidades.

# &nbsp;           </p>

# &nbsp;           

# &nbsp;           <div class="finance-calculator">

# &nbsp;               <div class="calculator-container">

# &nbsp;                   <div class="calculator-inputs">

# &nbsp;                       <h3>Configura tu financiación</h3>

# &nbsp;                       

# &nbsp;                       <div class="form-group">

# &nbsp;                           <label for="financeVehicle">Vehículo de interés</label>

# &nbsp;                           <select id="financeVehicle" class="form-control" required>

# &nbsp;                               <option value="">Selecciona un vehículo</option>

# &nbsp;                               <!-- Las opciones se llenarán con JavaScript -->

# &nbsp;                           </select>

# &nbsp;                       </div>

# &nbsp;                       

# &nbsp;                       <div class="form-group">

# &nbsp;                           <label for="vehiclePrice">Precio del vehículo</label>

# &nbsp;                           <input type="text" id="vehiclePrice" class="form-control" readonly>

# &nbsp;                       </div>

# &nbsp;                       

# &nbsp;                       <div class="form-group">

# &nbsp;                           <label for="downPayment">Pago inicial</label>

# &nbsp;                           <div style="position: relative;">

# &nbsp;                               <input type="number" id="downPayment" class="form-control" min="0" step="100000" placeholder="Ingresa el monto">

# &nbsp;                               <span style="position: absolute; right: 10px; top: 50%; transform: translateY(-50%); color: var(--gray); font-size: 12px;">Mínimo 10%</span>

# &nbsp;                           </div>

# &nbsp;                           <div id="downPaymentPercentage" style="font-size: 14px; color: var(--gray); margin-top: 5px;"></div>

# &nbsp;                           <div id="downPaymentError" class="error-message"></div>

# &nbsp;                       </div>

# &nbsp;                       

# &nbsp;                       <div class="form-group">

# &nbsp;                           <label for="loanTerm">Plazo (meses)</label>

# &nbsp;                           <input type="number" id="loanTerm" class="form-control" min="1" max="72" value="48" placeholder="1 a 72 meses">

# &nbsp;                       </div>

# &nbsp;                       

# &nbsp;                       <div class="form-group">

# &nbsp;                           <label for="financeName">Nombre completo \*</label>

# &nbsp;                           <input type="text" id="financeName" class="form-control" required>

# &nbsp;                           <div id="financeNameValidation" class="validation-message"></div>

# &nbsp;                       </div>

# &nbsp;                       

# &nbsp;                       <div class="form-row">

# &nbsp;                           <div class="form-group">

# &nbsp;                               <label for="financePhone">Teléfono \*</label>

# &nbsp;                               <input type="tel" id="financePhone" class="form-control" required>

# &nbsp;                               <div id="financePhoneValidation" class="validation-message"></div>

# &nbsp;                           </div>

# &nbsp;                           <div class="form-group">

# &nbsp;                               <label for="financeEmail">Correo electrónico \*</label>

# &nbsp;                               <input type="email" id="financeEmail" class="form-control" required>

# &nbsp;                               <div id="financeEmailValidation" class="validation-message"></div>

# &nbsp;                           </div>

# &nbsp;                       </div>

# &nbsp;                       

# &nbsp;                       <!-- Autorización de datos -->

# &nbsp;                       <div class="authorization-container">

# &nbsp;                           <p class="authorization-text">

# &nbsp;                               <strong>AUTORIZACIÓN DE TRATAMIENTO DE DATOS PERSONALES</strong><br>

# &nbsp;                               De conformidad con la Ley 1581 de 2012 y el Decreto Reglamentario 1377 de 2013, autorizo de manera voluntaria, previa, explícita, informada e inequívoca a CAPITAL CARS S.A.S. para tratar mis datos personales con la finalidad de contactarme, realizar cotizaciones, prestar los servicios solicitados, enviar información comercial y realizar actividades de mercadeo relacionadas con nuestros productos y servicios. Conozco que puedo ejercer mis derechos de acceso, corrección, actualización, supresión y revocación del consentimiento a través del correo electrónico capitalcarscolombia@gmail.com.

# &nbsp;                           </p>

# &nbsp;                           <div class="authorization-buttons">

# &nbsp;                               <button type="button" id="financeAcceptBtn" class="btn btn-success">

# &nbsp;                                   <i class="fas fa-check-circle"></i> Sí, autorizo

# &nbsp;                               </button>

# &nbsp;                               <button type="button" id="financeDeclineBtn" class="btn btn-danger">

# &nbsp;                                   <i class="fas fa-times-circle"></i> No autorizo

# &nbsp;                               </button>

# &nbsp;                           </div>

# &nbsp;                       </div>

# &nbsp;                   </div>

# &nbsp;                   

# &nbsp;                   <div class="calculator-results">

# &nbsp;                       <h3>Resultados de tu simulación</h3>

# &nbsp;                       

# &nbsp;                       <div class="result-item">

# &nbsp;                           <span>Pago inicial:</span>

# &nbsp;                           <span class="result-value" id="downPaymentResult">$0</span>

# &nbsp;                       </div>

# &nbsp;                       

# &nbsp;                       <div class="result-item">

# &nbsp;                           <span>Monto a financiar:</span>

# &nbsp;                           <span class="result-value" id="financedAmount">$0</span>

# &nbsp;                       </div>

# &nbsp;                       

# &nbsp;                       <div class="result-item">

# &nbsp;                           <span>Cuota mensual:</span>

# &nbsp;                           <span class="result-value" id="monthlyPayment">$0</span>

# &nbsp;                       </div>

# &nbsp;                       

# &nbsp;                       <div class="result-item">

# &nbsp;                           <span>Total a pagar:</span>

# &nbsp;                           <span class="result-value" id="totalPayment">$0</span>

# &nbsp;                       </div>

# &nbsp;                       

# &nbsp;                       <div class="result-item">

# &nbsp;                           <span>Intereses totales:</span>

# &nbsp;                           <span class="result-value" id="totalInterest">$0</span>

# &nbsp;                       </div>

# &nbsp;                       

# &nbsp;                       <div class="calculator-notice">

# &nbsp;                           <i class="fas fa-info-circle"></i> Esta es una simulación. Las condiciones finales pueden variar según el análisis de crédito.

# &nbsp;                       </div>

# &nbsp;                       

# &nbsp;                       <button id="financeWhatsAppBtn" class="btn" style="background-color: white; color: var(--primary); margin-top: 20px; width: 100%;" disabled>

# &nbsp;                           <i class="fab fa-whatsapp"></i> Solicitar Financiación por WhatsApp

# &nbsp;                       </button>

# &nbsp;                   </div>

# &nbsp;               </div>

# &nbsp;           </div>

# &nbsp;       </div>

# &nbsp;   </section>

# &nbsp;   

# &nbsp;   <section id="contacto" class="contact-section">

# &nbsp;       <div class="container">

# &nbsp;           <h2 class="section-title">Contáctanos</h2>

# &nbsp;           <p style="text-align: center; max-width: 700px; margin: 0 auto 40px; color: var(--gray);">

# &nbsp;               ¿Tienes preguntas? Estamos aquí para ayudarte. Completa el formulario y te contactaremos a la brevedad.

# &nbsp;           </p>

# &nbsp;           

# &nbsp;           <div class="contact-grid">

# &nbsp;               <div class="form-container">

# &nbsp;                   <form id="contactForm">

# &nbsp;                       <div class="form-row">

# &nbsp;                           <div class="form-group">

# &nbsp;                               <label for="contactName">Nombre completo \*</label>

# &nbsp;                               <input type="text" id="contactName" class="form-control" required>

# &nbsp;                               <div id="contactNameValidation" class="validation-message"></div>

# &nbsp;                           </div>

# &nbsp;                           <div class="form-group">

# &nbsp;                               <label for="contactPhone">Teléfono \*</label>

# &nbsp;                               <input type="tel" id="contactPhone" class="form-control" required>

# &nbsp;                               <div id="contactPhoneValidation" class="validation-message"></div>

# &nbsp;                           </div>

# &nbsp;                       </div>

# &nbsp;                       

# &nbsp;                       <div class="form-group">

# &nbsp;                           <label for="contactEmail">Correo electrónico \*</label>

# &nbsp;                           <input type="email" id="contactEmail" class="form-control" required>

# &nbsp;                           <div id="contactEmailValidation" class="validation-message"></div>

# &nbsp;                       </div>

# &nbsp;                       

# &nbsp;                       <div class="form-group">

# &nbsp;                           <label for="subject">Asunto</label>

# &nbsp;                           <select id="subject" class="form-control">

# &nbsp;                               <option value="">Selecciona un asunto</option>

# &nbsp;                               <option value="compra">Compra de vehículo</option>

# &nbsp;                               <option value="venta">Venta de vehículo</option>

# &nbsp;                               <option value="financiacion">Financiación</option>

# &nbsp;                               <option value="servicio">Servicio postventa</option>

# &nbsp;                               <option value="otro">Otro</option>

# &nbsp;                           </select>

# &nbsp;                       </div>

# &nbsp;                       

# &nbsp;                       <div class="form-group">

# &nbsp;                           <label for="message">Mensaje</label>

# &nbsp;                           <textarea id="message" class="form-control" rows="5"></textarea>

# &nbsp;                       </div>

# &nbsp;                       

# &nbsp;                       <!-- Autorización de datos -->

# &nbsp;                       <div class="authorization-container">

# &nbsp;                           <p class="authorization-text">

# &nbsp;                               <strong>AUTORIZACIÓN DE TRATAMIENTO DE DATOS PERSONALES</strong><br>

# &nbsp;                               De conformidad con la Ley 1581 de 2012 y el Decreto Reglamentario 1377 de 2013, autorizo de manera voluntaria, previa, explícita, informada e inequívoca a CAPITAL CARS S.A.S. para tratar mis datos personales con la finalidad de contactarme, realizar cotizaciones, prestar los servicios solicitados, enviar información comercial y realizar actividades de mercadeo relacionadas con nuestros productos y servicios. Conozco que puedo ejercer mis derechos de acceso, corrección, actualización, supresión y revocación del consentimiento a través del correo electrónico capitalcarscolombia@gmail.com.

# &nbsp;                           </p>

# &nbsp;                           <div class="authorization-buttons">

# &nbsp;                               <button type="button" id="contactAcceptBtn" class="btn btn-success">

# &nbsp;                                   <i class="fas fa-check-circle"></i> Sí, autorizo

# &nbsp;                               </button>

# &nbsp;                               <button type="button" id="contactDeclineBtn" class="btn btn-danger">

# &nbsp;                                   <i class="fas fa-times-circle"></i> No autorizo

# &nbsp;                               </button>

# &nbsp;                           </div>

# &nbsp;                       </div>

# &nbsp;                       

# &nbsp;                       <button type="submit" class="btn" style="width: 100%;" id="contactSubmitBtn" disabled>

# &nbsp;                           <i class="fab fa-whatsapp"></i> Enviar por WhatsApp

# &nbsp;                       </button>

# &nbsp;                   </form>

# &nbsp;               </div>

# &nbsp;               

# &nbsp;               <div class="contact-info">

# &nbsp;                   <h3>Información de Contacto</h3>

# &nbsp;                   <div class="contact-item">

# &nbsp;                       <i class="fas fa-phone"></i>

# &nbsp;                       <div>

# &nbsp;                           <strong>Teléfono</strong><br>

# &nbsp;                           +57 313 701 5502

# &nbsp;                       </div>

# &nbsp;                   </div>

# &nbsp;                   

# &nbsp;                   <div class="contact-item">

# &nbsp;                       <i class="fas fa-envelope"></i>

# &nbsp;                       <div>

# &nbsp;                           <strong>Correo electrónico</strong><br>

# &nbsp;                           capitalcarscolombia@gmail.com

# &nbsp;                       </div>

# &nbsp;                   </div>

# &nbsp;                   

# &nbsp;                   <div class="contact-item">

# &nbsp;                       <i class="fas fa-map-marker-alt"></i>

# &nbsp;                       <div>

# &nbsp;                           <strong>Ubicación</strong><br>

# &nbsp;                           Bogotá, Colombia

# &nbsp;                       </div>

# &nbsp;                   </div>

# &nbsp;                   

# &nbsp;                   <div class="contact-item">

# &nbsp;                       <i class="fas fa-clock"></i>

# &nbsp;                       <div>

# &nbsp;                           <strong>Horario de atención</strong><br>

# &nbsp;                           Lunes a Viernes: 8:00 AM - 6:00 PM<br>

# &nbsp;                           Sábados: 9:00 AM - 2:00 PM

# &nbsp;                       </div>

# &nbsp;                   </div>

# &nbsp;                   

# &nbsp;                   <div class="contact-item">

# &nbsp;                       <i class="fas fa-handshake"></i>

# &nbsp;                       <div>

# &nbsp;                           <strong>Aliados</strong><br>

# &nbsp;                           Dacar Autos

# &nbsp;                       </div>

# &nbsp;                   </div>

# &nbsp;               </div>

# &nbsp;           </div>

# &nbsp;       </div>

# &nbsp;   </section>

# &nbsp;   

# &nbsp;   <footer>

# &nbsp;       <div class="container">

# &nbsp;           <div class="footer-content">

# &nbsp;               <div class="footer-section">

# &nbsp;                   <h3>Capital Cars S.A.S</h3>

# &nbsp;                   <p>Especialistas en la compra y venta de vehículos de alta gama con los mejores estándares de calidad y servicio.</p>

# &nbsp;                   <p><i class="fas fa-star"></i> Vehículos certificados</p>

# &nbsp;                   <p><i class="fas fa-shield-alt"></i> Transacciones seguras</p>

# &nbsp;                   <p><i class="fas fa-handshake"></i> Asesoramiento experto</p>

# &nbsp;                   <p><i class="fas fa-handshake"></i> Aliados de <strong>Dacar Autos</strong></p>

# &nbsp;               </div>

# &nbsp;               

# &nbsp;               <div class="footer-section">

# &nbsp;                   <h3>Contacto</h3>

# &nbsp;                   <p><i class="fas fa-phone"></i> +57 313 701 5502</p>

# &nbsp;                   <p><i class="fas fa-envelope"></i> capitalcarscolombia@gmail.com</p>

# &nbsp;                   <p><i class="fas fa-map-marker-alt"></i> Bogotá, Colombia</p>

# &nbsp;                   <div style="margin-top: 15px;">

# &nbsp;                       <a href="https://www.facebook.com/profile.php?id=61584347432994" target="\_blank" style="color: white; margin-right: 15px; font-size: 20px;"><i class="fab fa-facebook"></i></a>

# &nbsp;                       <a href="https://www.instagram.com/capitalcarscolombia/?hl=es" target="\_blank" style="color: white; margin-right: 15px; font-size: 20px;"><i class="fab fa-instagram"></i></a>

# &nbsp;                       <a href="https://wa.me/573137015502" target="\_blank" style="color: white; font-size: 20px;"><i class="fab fa-whatsapp"></i></a>

# &nbsp;                   </div>

# &nbsp;               </div>

# &nbsp;               

# &nbsp;               <div class="footer-section">

# &nbsp;                   <h3>Horario de Atención</h3>

# &nbsp;                   <p><i class="fas fa-clock"></i> Lunes a Viernes: 8:00 AM - 6:00 PM</p>

# &nbsp;                   <p><i class="fas fa-clock"></i> Sábados: 9:00 AM - 2:00 PM</p>

# &nbsp;                   <p><i class="fas fa-clock"></i> Domingos: Cerrado</p>

# &nbsp;               </div>

# &nbsp;               

# &nbsp;               <div class="footer-section">

# &nbsp;                   <h3>Enlaces Rápidos</h3>

# &nbsp;                   <p><a href="#vehiculos" style="color: rgba(255, 255, 255, 0.8); text-decoration: none;">Vehículos Disponibles</a></p>

# &nbsp;                   <p><a href="#vender" style="color: rgba(255, 255, 255, 0.8); text-decoration: none;">Vender Mi Vehículo</a></p>

# &nbsp;                   <p><a href="#financiacion" style="color: rgba(255, 255, 255, 0.8); text-decoration: none;">Simulador de Crédito</a></p>

# &nbsp;                   <p><a href="#contacto" style="color: rgba(255, 255, 255, 0.8); text-decoration: none;">Contacto</a></p>

# &nbsp;               </div>

# &nbsp;           </div>

# &nbsp;           

# &nbsp;           <div class="copyright">

# &nbsp;               \&copy; 2025 Capital Cars S.A.S. Todos los derechos reservados.

# &nbsp;           </div>

# &nbsp;       </div>

# &nbsp;   </footer>

# &nbsp;   

# &nbsp;   <!-- Modal para mostrar descripción del vehículo -->

# &nbsp;   <div id="vehicleModal" class="modal">

# &nbsp;       <div class="modal-content">

# &nbsp;           <span class="close-modal">\&times;</span>

# &nbsp;           <div class="modal-header">

# &nbsp;               <h2 class="modal-title" id="modalVehicleTitle"></h2>

# &nbsp;               <p class="modal-subtitle" id="modalVehicleSubtitle"></p>

# &nbsp;           </div>

# &nbsp;           <div class="modal-body">

# &nbsp;               <img id="modalVehicleImage" class="modal-image" src="" alt="">

# &nbsp;               <div id="modalVehicleDescription"></div>

# &nbsp;           </div>

# &nbsp;       </div>

# &nbsp;   </div>

# &nbsp;   

# &nbsp;   <!-- Modal de confirmación para financiación -->

# &nbsp;   <div id="financeConfirmationModal" class="confirmation-modal">

# &nbsp;       <div class="confirmation-content">

# &nbsp;           <div class="confirmation-icon">

# &nbsp;               <i class="fas fa-exclamation-circle"></i>

# &nbsp;           </div>

# &nbsp;           <h3 class="confirmation-title">Confirmación de Solicitud</h3>

# &nbsp;           <p class="confirmation-text">

# &nbsp;               <strong>Importante:</strong> Esta simulación está sujeta a perfil y estudio crediticio. 

# &nbsp;               La aprobación final dependerá del análisis de su historial crediticio y capacidad de pago.

# &nbsp;           </p>

# &nbsp;           <p class="confirmation-text">

# &nbsp;               ¿Confirma que desea enviar su solicitud de financiación por WhatsApp?

# &nbsp;           </p>

# &nbsp;           <div class="confirmation-buttons">

# &nbsp;               <button id="confirmFinanceBtn" class="btn btn-confirm">

# &nbsp;                   <i class="fas fa-check"></i> Sí, enviar

# &nbsp;               </button>

# &nbsp;               <button id="cancelFinanceBtn" class="btn btn-cancel">

# &nbsp;                   <i class="fas fa-times"></i> Cancelar

# &nbsp;               </button>

# &nbsp;           </div>

# &nbsp;       </div>

# &nbsp;   </div>

# &nbsp;   

# &nbsp;   <script>

# &nbsp;       // Datos de vehículos actualizados con todos los carros

# &nbsp;       const vehicles = \[

# &nbsp;           {

# &nbsp;               id: 1,

# &nbsp;               name: "HYUNDAI TUCSON PREMIUM GL AT",

# &nbsp;               image: "https://images.unsplash.com/photo-1603584173870-7f23fdae1b7a?ixlib=rb-4.0.3\&auto=format\&fit=crop\&w=500\&q=80",

# &nbsp;               price: "$90.900.000",

# &nbsp;               year: "2019",

# &nbsp;               mileage: "70.000 km",

# &nbsp;               transmission: "Automático/secuencial",

# &nbsp;               fuel: "Gasolina",

# &nbsp;               location: "Bogotá",

# &nbsp;               description: `

# &nbsp;                   <div class="features-list">

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Excelente estado</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Placa 4 Bogotá</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Color Negro</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 5 pasajeros</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Motor 2.000 cc 16 válvulas</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Automático/secuencial</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 70.000 kms</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Aire acondicionado</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Sensor de lluvia</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Sensor de luces</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Sensor de proximidad en puertas</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Dirección electrónica asistida</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Botón de encendido</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 6 Airbag</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Frenos ABS + EBD</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Control de descenso</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Control de tracción en carretera</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Control vectorial de torque</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Vidrios Eléctricos x4 one touch</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Espejos eléctricos con direccionales</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Rines de lujo</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Comandos de radio en el volante</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Volante graduable en altura y profundidad</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Radio táctil con conectividad bluetooth</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Techo panorámico</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Bloqueo Central</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Alarma</div>

# &nbsp;                   </div>

# &nbsp;               `,

# &nbsp;               contact: "📞 +57 313 701 5502",

# &nbsp;               sold: false

# &nbsp;           },

# &nbsp;           {

# &nbsp;               id: 2,

# &nbsp;               name: "SUZUKI SWIFT HIBRIDO",

# &nbsp;               image: "https://images.unsplash.com/photo-1550355291-bbee04a92027?ixlib=rb-4.0.3\&auto=format\&fit=crop\&w=500\&q=80",

# &nbsp;               price: "$63.900.000",

# &nbsp;               year: "2022",

# &nbsp;               mileage: "56.000 km",

# &nbsp;               transmission: "Mecánico 4x2",

# &nbsp;               fuel: "Híbrido",

# &nbsp;               location: "Bogotá",

# &nbsp;               description: `

# &nbsp;                   <div class="features-list">

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Excelente estado</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Vehículo asegurable</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Híbrido ligero</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> SIN PICO Y PLACA</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Placa 8 Bogotá</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Color Blanco</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 5 pasajeros</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 5 puertas</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Hatchback</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Motor 1.250 cc 16 válvulas</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Mecánico 4x2</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 56.000 kms</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Dirección electrónica asistida</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Aire acondicionado</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Encendido con llave</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Frenos ABS, EBD</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Vidrios Eléctricos x4</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Espejos eléctricos</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Rines de lujo</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Freno de disco delantero</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Columna de dirección ajustable</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 6 airbags</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Señal de frenado de emergencia</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Asistencia en pendiente</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Sistema de frenos ABS+EBD</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Control de tracción en carretera</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Luces LED</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Luces traseras LED</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Exploradoras</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Sensor de reversa con cámara</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Radio con pantalla touch multifuncional con conectividad bluetooth</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Con Android auto y/o applecarplay</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Puerto de carga inalámbrico</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Botón multicomando</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Sensor de lluvia</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Sistema de start stop</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Alarma con módulo elevavidrios</div>

# &nbsp;                   </div>

# &nbsp;               `,

# &nbsp;               contact: "📞 +57 313 701 5502",

# &nbsp;               sold: true

# &nbsp;           },

# &nbsp;           {

# &nbsp;               id: 3,

# &nbsp;               name: "FORD EDGE LIMITED 4X4 2014",

# &nbsp;               image: "https://images.unsplash.com/photo-1580273916550-e323be2ae537?ixlib=rb-4.0.3\&auto=format\&fit=crop\&w=500\&q=80",

# &nbsp;               price: "$48.900.000",

# &nbsp;               year: "2014",

# &nbsp;               mileage: "100.000 km",

# &nbsp;               transmission: "Automático/secuencial",

# &nbsp;               fuel: "Gasolina",

# &nbsp;               location: "Bogotá",

# &nbsp;               description: `

# &nbsp;                   <div class="features-list">

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Excelente estado</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Placa 2 Bogotá</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Color Plata puro</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 5 pasajeros</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Motor 3.500 24V V6</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Automático/secuencial</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 100.000 kms</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Aire acondicionado bi-zona</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Sensor de lluvia</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Sensor de luces</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Sensor de proximidad en las 4 puertas y baúl</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Dirección hidráulica</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Botón de encendido</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 7 Airbag</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Frenos ABS + EBD</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Control de tracción en carretera</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Control vectorial de torque</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Vidrios Eléctricos x4 one touch</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Espejos eléctricos con direccionales</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Sensores de reversa traseros con cámara</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Rines de lujo</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Comandos de radio en el volante</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Sistema de velocidad crucero</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Volante graduable en altura y profundidad</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Radio Sony con pantalla táctil y conectividad bluetooth</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Bloqueo Central</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Tapicería en cuero</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Silla de conductor y copiloto eléctricas de 10 vías con calefacción</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Silla del conductor con memorias</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Alerta de punto ciego en espejos retrovisores</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Apertura remota puerta baúl</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Techo panorámico con apertura</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Alarma</div>

# &nbsp;                   </div>

# &nbsp;               `,

# &nbsp;               contact: "📞 +57 313 701 5502",

# &nbsp;               sold: true

# &nbsp;           },

# &nbsp;           {

# &nbsp;               id: 4,

# &nbsp;               name: "CITROEN C4 CACTUS SHINE 1.6L TURBO",

# &nbsp;               image: "https://images.unsplash.com/photo-1621007947382-bb3c3994e3fb?ixlib=rb-4.0.3\&auto=format\&fit=crop\&w=500\&q=80",

# &nbsp;               price: "$68.900.000",

# &nbsp;               year: "2022",

# &nbsp;               mileage: "40.000 km",

# &nbsp;               transmission: "Automático secuencial de 6 marchas",

# &nbsp;               fuel: "Gasolina",

# &nbsp;               location: "Bogotá",

# &nbsp;               description: `

# &nbsp;                   <div class="features-list">

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Excelente estado</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Vehículo asegurable</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Placa 0 Bogotá</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Color Plata</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Camioneta</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 5 puestos</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Motor 1600L Turbo</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Automático secuencial de 6 marchas</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 40.000 kms</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Aire acondicionado</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Botón de encendido</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Modos de manejo (nieve, barro, etc...)</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 2 Airbag</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Frenos ABS+EBD</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Control de tracción en carretera</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Asistencia en pendientes</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Vidrios Eléctricos x4</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Espejos eléctricos con direccionales incorporadas</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Sensor de reversa con cámara</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Tapicería en cuero</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Pantalla de instrumentos digital</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Rines de lujo bitono</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Comandos de radio en el volante</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Volante graduable en altura y profundidad con comandos de radio</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Sistema de velocidad crucero</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Dirección electrónica asistida</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Luz de marcha diurna HID</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Luces automáticas</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Exploradoras</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Apertura remota de baúl</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Pantalla táctil multifuncional con Android auto y/o Apple carplay</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Bloqueo Central</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Alarma</div>

# &nbsp;                   </div>

# &nbsp;               `,

# &nbsp;               contact: "📞 +57 313 701 5502",

# &nbsp;               sold: false

# &nbsp;           },

# &nbsp;           {

# &nbsp;               id: 5,

# &nbsp;               name: "TOYOTA RAV4 LE HIBRIDO 4X4 2.5L",

# &nbsp;               image: "https://images.unsplash.com/photo-1563720223485-41b7d8334c59?ixlib=rb-4.0.3\&auto=format\&fit=crop\&w=500\&q=80",

# &nbsp;               price: "$167.900.000",

# &nbsp;               year: "2021",

# &nbsp;               mileage: "27.000 km",

# &nbsp;               transmission: "Automático electrónico e-CVT",

# &nbsp;               fuel: "Híbrido",

# &nbsp;               location: "Bogotá",

# &nbsp;               description: `

# &nbsp;                   <div class="features-list">

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Vehículo asegurable</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Excelente estado</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Km 27.000</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Placa 4 Bogotá</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Color Plata</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 5 puestos</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 1 MOTOR A COMBUSTIÓN DE 2,5 LITROS</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 4 MOTORES ELÉCTRICOS</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> SISTEMA TRACCIÓN 4WD (E-FOUR)</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> POTENCIA COMBINADA DE 219 CABALLOS DE FUERZA</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> MAXIMO TORQUE 265 Nm</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> TRANSMISIÓN AUTOMÁTICA ELÉCTRONICA e-CVT</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> TIMON AJUSTABEL EN ALTURA Y PROFUNDIDAD</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> DIRECCION ELECTRONICA ASISTIDA</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> ASISTENTES DE FRENADO ABS + EBD + BA</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> CONTROL DE ESTABILIDAD VEHÍCULAR (VSC)</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> SISTEMA DE PRE-COLISIÓN (PCS)</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> CONTROL CRUCERO</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> RADIO PANTALLA TÁCTIL DE 7" PULGADAS</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> CONECTIVIDAD MULTIPLE</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> CAMARA DE REVERSA</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> TAPICERIA EN TELA DE ALTA RESISTENCIA</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> SILLA CONDUCTOR CON AJUSTE MANUAL: DESLIZA + RECLINA + ALTURA</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> AIRE ACONDICIONADO AUTOMÁTICO BI-ZONA</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 7 AIRBAGS PARA MEJOR SEGURIDAD</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> FAROS Y EXPLORADORAS CON TECNOLOGÍA LED</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> RINES DE ALUMINIO DE 17" PULGADAS</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> FRENO DE ESTACIONAMIENTO ELECTRÓNICO + FUNCIÓN "AUTO HOLD"</div>

# &nbsp;                   </div>

# &nbsp;               `,

# &nbsp;               contact: "📞 +57 313 701 5502",

# &nbsp;               sold: false

# &nbsp;           },

# &nbsp;           {

# &nbsp;               id: 6,

# &nbsp;               name: "NISSAN TIIDA EMOTION MT 2012",

# &nbsp;               image: "https://images.unsplash.com/photo-1592198084033-aade902d1aae?ixlib=rb-4.0.3\&auto=format\&fit=crop\&w=500\&q=80",

# &nbsp;               price: "$30.900.000",

# &nbsp;               year: "2012",

# &nbsp;               mileage: "105.000 km",

# &nbsp;               transmission: "Mecánico",

# &nbsp;               fuel: "Gasolina",

# &nbsp;               location: "Bogotá",

# &nbsp;               description: `

# &nbsp;                   <div class="features-list">

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Excelente estado</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Vehículo asegurable</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Placa 2 Bogotá</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Color Plateado</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 5 puestos</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Motor 1.800 cc</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Mecánico</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 105.000 kms</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Aire acondicionado</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 4 Airbag</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Frenos ABS, EBD</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Vidrios Eléctricos x4</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Espejos eléctricos</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Sensor de reversa</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Rines de lujo</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Volante graduable en altura</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Dirección electrónica</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Silla de conductor graduable en altura y profundidad</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Bloqueo Central</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Soat vigente para el febrero de 2026</div>

# &nbsp;                   </div>

# &nbsp;               `,

# &nbsp;               contact: "📞 +57 313 701 5502",

# &nbsp;               sold: false

# &nbsp;           },

# &nbsp;           {

# &nbsp;               id: 7,

# &nbsp;               name: "VOLKSWAGEN GOL COMFORTLINE 1.6",

# &nbsp;               image: "https://images.unsplash.com/photo-1603584173870-7f23fdae1b7a?ixlib=rb-4.0.3\&auto=format\&fit=crop\&w=500\&q=80",

# &nbsp;               price: "$42.900.000",

# &nbsp;               year: "2017",

# &nbsp;               mileage: "41.000 km",

# &nbsp;               transmission: "Mecánico",

# &nbsp;               fuel: "Gasolina",

# &nbsp;               location: "Bogotá",

# &nbsp;               description: `

# &nbsp;                   <div class="features-list">

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Excelente estado</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Vehículo asegurable</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Placa 2 Bogotá</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Color Plateado</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 5 puestos</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Motor 1.600 cc</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Mecánico</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 41.000 kms</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Aire acondicionado</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Doble Airbag</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Frenos ABS, EBD</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Vidrios Eléctricos x2</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Espejos manuales</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Sensor de reversa</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Rines de lujo</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Volante graduable en altura</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Radio con conectividad Bluetooth</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Bloqueo Central</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Alarma</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Exploradoras</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Soat vigente para el febrero de 2026</div>

# &nbsp;                   </div>

# &nbsp;               `,

# &nbsp;               contact: "📞 +57 313 701 5502",

# &nbsp;               sold: true

# &nbsp;           },

# &nbsp;           {

# &nbsp;               id: 8,

# &nbsp;               name: "FORD ECOSPORT FREESTYLE 4X4 AT",

# &nbsp;               image: "https://images.unsplash.com/photo-1603584173870-7f23fdae1b7a?ixlib=rb-4.0.3\&auto=format\&fit=crop\&w=500\&q=80",

# &nbsp;               price: "$65.900.000",

# &nbsp;               year: "2020",

# &nbsp;               mileage: "49.000 km",

# &nbsp;               transmission: "Automático 6 velocidades modo secuencial",

# &nbsp;               fuel: "Gasolina",

# &nbsp;               location: "Bogotá",

# &nbsp;               description: `

# &nbsp;                   <div class="features-list">

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Excelente estado</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Vehículo asegurable</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Km 49.000</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Placa 5 Bogotá</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Color Negro</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 5 puestos</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 2.0L 4 cilindros 16 válvulas</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Transmisión automática 6 velocidades modo secuencial</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Levas en el volante</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Tracción 4x4 inteligente</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Asistencia de arranque en pendiente</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Rines de lujo 16"</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Dirección electrónica asistida</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Frenos de discos delanteros campana traseros</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> ABS + EBD</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Control ESC</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Bloqueo central</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Airbag conductor y copiloto</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> ISOFIX</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Aire Acondicionado</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Vidrios eléctricos X 4</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Sensor de reversa con cámara</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Retrovisores eléctricos</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Pantalla táctil 8 pulgadas con Sync 3</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Conectividad Android auto y/o apple carplay</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Puertos de carga USB</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Faros Halógenos + Exploradoras</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Luz de marcha led</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Barras de techo</div>

# &nbsp;                   </div>

# &nbsp;               `,

# &nbsp;               contact: "📞 +57 313 701 5502",

# &nbsp;               sold: false

# &nbsp;           },

# &nbsp;           {

# &nbsp;               id: 9,

# &nbsp;               name: "PEUGEOT 2008 GT LINE 2024",

# &nbsp;               image: "https://images.unsplash.com/photo-1603584173870-7f23fdae1b7a?ixlib=rb-4.0.3\&auto=format\&fit=crop\&w=500\&q=80",

# &nbsp;               price: "$96.900.000",

# &nbsp;               year: "2024",

# &nbsp;               mileage: "29.000 km",

# &nbsp;               transmission: "Caja automática secuencial de 6 velocidades",

# &nbsp;               fuel: "Gasolina",

# &nbsp;               location: "Bogotá",

# &nbsp;               description: `

# &nbsp;                   <div class="features-list">

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Excelente estado</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Kms 29.000</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Placa 0 Bogotá</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> UNICO DUEÑO</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Dirección electrónica asistida</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Caja automática secuencial de 6 velocidades</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Luces de circulación diurna Led</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Luces Eco LED automáticas</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Limpiabrisas con sensor de lluvia</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Espejos retrovisores de ajuste eléctrico con desempañador</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Volante multifunción forrado en cuero ajustable en altura y profundidad</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Asientos delanteros manuales</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Silla del conductor graduable en altura</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Segunda fila de asientos abatible 60/40</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Espejo retrovisor electrocromático</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Direccional en espejos con luz led</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Alerta de punto ciego en espejos retrovisores</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Espejos con abatibles electronicamente</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Sistema multimedia con pantalla de 7" AM/FM/USB/AUX IN/Bluetooth compatible with Mirror Link, Apple CarPlay y Android Auto</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Puertos USB, uno adelante de datos y carga</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Sistema de audio con seis altavoces</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> A/A automático</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Vidrios eléctricos con función de un solo toque</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Panel de instrumentos análogo con clúster LCD de 3,5" a color</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Control de crucero y limitador de velocidad</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 6 airbags</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Asistencia de frenado de urgencia (EBA)</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Antideslizamiento de ruedas (ASR)</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Control electrónico de estabilidad (ESP)</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Asistencia de estabilidad de remolque (TSA)</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Asistente de arranque en pendiente (HSA)</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Monitoreo de presión de llantas</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Cámara de reversa</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Freno de mano electronico</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Sensores de estacionamiento delanteros y traseros</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Techo panorámico</div>

# &nbsp;                   </div>

# &nbsp;               `,

# &nbsp;               contact: "📞 310 5834150",

# &nbsp;               sold: false

# &nbsp;           },

# &nbsp;           {

# &nbsp;               id: 10,

# &nbsp;               name: "VOLKSWAGEN VIRTUS TRENDLINE MT 1.6 CC",

# &nbsp;               image: "https://images.unsplash.com/photo-1603584173870-7f23fdae1b7a?ixlib=rb-4.0.3\&auto=format\&fit=crop\&w=500\&q=80",

# &nbsp;               price: "$61.900.000",

# &nbsp;               year: "2023",

# &nbsp;               mileage: "40.000 km",

# &nbsp;               transmission: "Mecánico",

# &nbsp;               fuel: "Gasolina",

# &nbsp;               location: "Bogotá",

# &nbsp;               description: `

# &nbsp;                   <div class="features-list">

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Excelente estado</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Vehículo asegurable</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Placa 5 Bogotá</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Color Gris</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 5 puestos</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Motor 1.600 cc 16V</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Mecanico</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 40.000 kms</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Aire acondicionado</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 4 Airbag</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Frenos ABS+EBD</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Control de tracción en carretera</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Vidrios Eléctricos x4 con modulo elevavidrios</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Espejos eléctricos con direccionales incorporadas</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Tapicería en tela de alta resistencia</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Pantalla de instrumentos digital</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Rines con copas</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Comandos de radio en el volante</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Volante graduable en altura y profundidad con comandos de radio</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Dirección electrónica asistida</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Luz de marcha diurna HID</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Luces automáticas</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Exploradoras</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Apertura remota de baúl</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Pantalla táctil multifuncional con Android auto y/o Apple carplay</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Bloqueo Central</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Alarma</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Soat febrero de 2026</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Recibimos su usado en parte de pago</div>

# &nbsp;                   </div>

# &nbsp;               `,

# &nbsp;               contact: "📞 +57 313 701 5502",

# &nbsp;               sold: false

# &nbsp;           },

# &nbsp;           {

# &nbsp;               id: 11,

# &nbsp;               name: "NISSAN KICKS ADVANCE AT 2023",

# &nbsp;               image: "https://images.unsplash.com/photo-1603584173870-7f23fdae1b7a?ixlib=rb-4.0.3\&auto=format\&fit=crop\&w=500\&q=80",

# &nbsp;               price: "$83.900.000",

# &nbsp;               year: "2023",

# &nbsp;               mileage: "36.000 km",

# &nbsp;               transmission: "Caja automática secuencial 4x2",

# &nbsp;               fuel: "Gasolina",

# &nbsp;               location: "Bogotá",

# &nbsp;               description: `

# &nbsp;                   <div class="features-list">

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Excelente estado</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Vehículo asegurable</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Placa 9 Bogotá</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Color Plata</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 5 pasajeros</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 5 puertas</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Camioneta</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Motor 1.600 cc 16 válvulas</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Cadena de repartición</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Caja automática secuencial 4x2</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 36.000 kms</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Dirección electrónica asistida</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Aire acondicionado</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Frenos ABS, EBD</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Vidrios eléctricos X 4</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Espejos electricos</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Freno de disco delantero</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Faros halogenos</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Exploradoras HID</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Sistema de velocidad crucero</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Sensor de proximidad en puertas</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Boton de encendido</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Bloqueo central</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Radio de pantalla con conectividad bluetooth</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Sensor of reversa con camara</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Soat vigente para julio de 2026</div>

# &nbsp;                   </div>

# &nbsp;               `,

# &nbsp;               contact: "📞 +57 313 701 5502",

# &nbsp;               sold: false

# &nbsp;           },

# &nbsp;           {

# &nbsp;               id: 12,

# &nbsp;               name: "RENAULT LOGAN LIFE MT 2023",

# &nbsp;               image: "https://images.unsplash.com/photo-1603584173870-7f23fdae1b7a?ixlib=rb-4.0.3\&auto=format\&fit=crop\&w=500\&q=80",

# &nbsp;               price: "$48.900.000",

# &nbsp;               year: "2023",

# &nbsp;               mileage: "56.000 km",

# &nbsp;               transmission: "Mecánico",

# &nbsp;               fuel: "Gasolina",

# &nbsp;               location: "Bogotá",

# &nbsp;               description: `

# &nbsp;                   <div class="features-list">

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Excelente estado</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Vehículo asegurable</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Motor 1.600 cc</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Mecanico</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> 56.000 kms</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Aire acondicionado</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Doble Airbag</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Frenos ABS, EBD</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Vidrios Eléctricos delanteros</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Bloqueo Central</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Espejos manuales con direccionales</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Manijas y espejos bodycolor</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Rin con copas</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Tapicería en tela de alta resistencia</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Radio con conectividad bluetooth</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Comando de radio satelital</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Alarma</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Kit de seguridad, pelicula de seguridad, pernos de seguridad y seguro de lunas</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Soat para mayo de 2026</div>

# &nbsp;                       <div class="feature-item"><i class="fas fa-check-circle"></i> Recibimos su usado en parte de pago</div>

# &nbsp;                   </div>

# &nbsp;               `,

# &nbsp;               contact: "📞 310 5834150",

# &nbsp;               sold: false

# &nbsp;           }

# &nbsp;       ];

# 

# &nbsp;       // Función para cargar vehículos en la página

# &nbsp;       function loadVehicles() {

# &nbsp;           const container = document.getElementById('vehiclesContainer');

# &nbsp;           container.innerHTML = '<div class="loading">Cargando vehículos...</div>';

# &nbsp;           

# &nbsp;           setTimeout(() => {

# &nbsp;               container.innerHTML = '';

# &nbsp;               vehicles.forEach(vehicle => {

# &nbsp;                   const vehicleCard = document.createElement('div');

# &nbsp;                   vehicleCard.className = `vehicle-card ${vehicle.sold ? 'sold' : ''}`;

# &nbsp;                   vehicleCard.innerHTML = `

# &nbsp;                       <div class="vehicle-image">

# &nbsp;                           <img src="${vehicle.image}" alt="${vehicle.name}" loading="lazy">

# &nbsp;                           ${vehicle.sold ? '<div class="sold-badge">VENDIDO</div>' : ''}

# &nbsp;                           ${vehicle.sold ? '<div class="sold-overlay"><div class="sold-text">VENDIDO</div></div>' : ''}

# &nbsp;                       </div>

# &nbsp;                       <div class="vehicle-details">

# &nbsp;                           <h3 class="vehicle-title">${vehicle.name}</h3>

# &nbsp;                           <div class="vehicle-info">

# &nbsp;                               <div class="vehicle-info-item">

# &nbsp;                                   <span>Año:</span>

# &nbsp;                                   <span>${vehicle.year}</span>

# &nbsp;                               </div>

# &nbsp;                               <div class="vehicle-info-item">

# &nbsp;                                   <span>Kilometraje:</span>

# &nbsp;                                   <span>${vehicle.mileage}</span>

# &nbsp;                               </div>

# &nbsp;                               <div class="vehicle-info-item">

# &nbsp;                                   <span>Transmisión:</span>

# &nbsp;                                   <span>${vehicle.transmission}</span>

# &nbsp;                               </div>

# &nbsp;                               <div class="vehicle-info-item">

# &nbsp;                                   <span>Combustible:</span>

# &nbsp;                                   <span>${vehicle.fuel}</span>

# &nbsp;                               </div>

# &nbsp;                               <div class="vehicle-info-item">

# &nbsp;                                   <span>Ubicación:</span>

# &nbsp;                                   <span>${vehicle.location}</span>

# &nbsp;                               </div>

# &nbsp;                           </div>

# &nbsp;                           <div class="vehicle-price">${vehicle.price}</div>

# &nbsp;                           <div class="vehicle-actions">

# &nbsp;                               ${vehicle.sold ? 

# &nbsp;                                   `<button class="btn btn-disabled" disabled>

# &nbsp;                                       <i class="fab fa-whatsapp"></i> Vendido

# &nbsp;                                   </button>

# &nbsp;                                   <button class="btn btn-description" onclick="showVehicleDescription(${vehicle.id})">

# &nbsp;                                       <i class="fas fa-info-circle"></i> Descripción

# &nbsp;                                   </button>` : 

# &nbsp;                                   `<a href="https://wa.me/573137015502?text=Hola,%20estoy%20interesado%20en%20el%20${encodeURIComponent(vehicle.name)}" class="btn btn-whatsapp" target="\_blank">

# &nbsp;                                       <i class="fab fa-whatsapp"></i> WhatsApp

# &nbsp;                                   </a>

# &nbsp;                                   <button class="btn btn-description" onclick="showVehicleDescription(${vehicle.id})">

# &nbsp;                                       <i class="fas fa-info-circle"></i> Descripción

# &nbsp;                                   </button>`

# &nbsp;                               }

# &nbsp;                           </div>

# &nbsp;                       </div>

# &nbsp;                   `;

# &nbsp;                   container.appendChild(vehicleCard);

# &nbsp;               });

# &nbsp;           }, 500);

# &nbsp;       }

# 

# &nbsp;       // Función para mostrar la descripción del vehículo en un modal

# &nbsp;       function showVehicleDescription(id) {

# &nbsp;           const vehicle = vehicles.find(v => v.id === id);

# &nbsp;           if (vehicle) {

# &nbsp;               const modal = document.getElementById('vehicleModal');

# &nbsp;               const modalTitle = document.getElementById('modalVehicleTitle');

# &nbsp;               const modalSubtitle = document.getElementById('modalVehicleSubtitle');

# &nbsp;               const modalImage = document.getElementById('modalVehicleImage');

# &nbsp;               const modalDescription = document.getElementById('modalVehicleDescription');

# &nbsp;               

# &nbsp;               modalTitle.textContent = vehicle.name;

# &nbsp;               modalSubtitle.textContent = `${vehicle.year} | ${vehicle.mileage} | ${vehicle.location}`;

# &nbsp;               modalImage.src = vehicle.image;

# &nbsp;               modalImage.alt = vehicle.name;

# &nbsp;               modalDescription.innerHTML = vehicle.description;

# &nbsp;               

# &nbsp;               modal.style.display = 'block';

# &nbsp;           }

# &nbsp;       }

# 

# &nbsp;       // Función para aplicar filtros a los vehículos

# &nbsp;       function applyFilters() {

# &nbsp;           const statusFilter = document.getElementById('filterStatus').value;

# &nbsp;           const priceFilter = document.getElementById('filterPrice').value;

# &nbsp;           const yearFilter = document.getElementById('filterYear').value;

# &nbsp;           const fuelFilter = document.getElementById('filterFuel').value;

# &nbsp;           

# &nbsp;           const container = document.getElementById('vehiclesContainer');

# &nbsp;           container.innerHTML = '';

# &nbsp;           

# &nbsp;           const filteredVehicles = vehicles.filter(vehicle => {

# &nbsp;               // Filtrar por estado

# &nbsp;               if (statusFilter === 'available' \&\& vehicle.sold) return false;

# &nbsp;               if (statusFilter === 'sold' \&\& !vehicle.sold) return false;

# &nbsp;               

# &nbsp;               // Filtrar por precio

# &nbsp;               if (priceFilter !== 'all') {

# &nbsp;                   const priceNumber = parseInt(vehicle.price.replace(/\\D/g, ''));

# &nbsp;                   if (priceNumber > parseInt(priceFilter)) return false;

# &nbsp;               }

# &nbsp;               

# &nbsp;               // Filtrar por año

# &nbsp;               if (yearFilter !== 'all') {

# &nbsp;                   if (parseInt(vehicle.year) < parseInt(yearFilter)) return false;

# &nbsp;               }

# &nbsp;               

# &nbsp;               // Filtrar por combustible

# &nbsp;               if (fuelFilter !== 'all' \&\& vehicle.fuel !== fuelFilter) return false;

# &nbsp;               

# &nbsp;               return true;

# &nbsp;           });

# &nbsp;           

# &nbsp;           if (filteredVehicles.length === 0) {

# &nbsp;               container.innerHTML = '<div class="loading">No se encontraron vehículos que coincidan con los filtros seleccionados.</div>';

# &nbsp;               return;

# &nbsp;           }

# &nbsp;           

# &nbsp;           filteredVehicles.forEach(vehicle => {

# &nbsp;               const vehicleCard = document.createElement('div');

# &nbsp;               vehicleCard.className = `vehicle-card ${vehicle.sold ? 'sold' : ''}`;

# &nbsp;               vehicleCard.innerHTML = `

# &nbsp;                   <div class="vehicle-image">

# &nbsp;                       <img src="${vehicle.image}" alt="${vehicle.name}" loading="lazy">

# &nbsp;                       ${vehicle.sold ? '<div class="sold-badge">VENDIDO</div>' : ''}

# &nbsp;                       ${vehicle.sold ? '<div class="sold-overlay"><div class="sold-text">VENDIDO</div></div>' : ''}

# &nbsp;                   </div>

# &nbsp;                   <div class="vehicle-details">

# &nbsp;                       <h3 class="vehicle-title">${vehicle.name}</h3>

# &nbsp;                       <div class="vehicle-info">

# &nbsp;                           <div class="vehicle-info-item">

# &nbsp;                               <span>Año:</span>

# &nbsp;                               <span>${vehicle.year}</span>

# &nbsp;                           </div>

# &nbsp;                           <div class="vehicle-info-item">

# &nbsp;                               <span>Kilometraje:</span>

# &nbsp;                               <span>${vehicle.mileage}</span>

# &nbsp;                           </div>

# &nbsp;                           <div class="vehicle-info-item">

# &nbsp;                               <span>Transmisión:</span>

# &nbsp;                               <span>${vehicle.transmission}</span>

# &nbsp;                           </div>

# &nbsp;                           <div class="vehicle-info-item">

# &nbsp;                               <span>Combustible:</span>

# &nbsp;                               <span>${vehicle.fuel}</span>

# &nbsp;                           </div>

# &nbsp;                           <div class="vehicle-info-item">

# &nbsp;                               <span>Ubicación:</span>

# &nbsp;                               <span>${vehicle.location}</span>

# &nbsp;                           </div>

# &nbsp;                       </div>

# &nbsp;                       <div class="vehicle-price">${vehicle.price}</div>

# &nbsp;                       <div class="vehicle-actions">

# &nbsp;                           ${vehicle.sold ? 

# &nbsp;                               `<button class="btn btn-disabled" disabled>

# &nbsp;                                   <i class="fab fa-whatsapp"></i> Vendido

# &nbsp;                               </button>

# &nbsp;                               <button class="btn btn-description" onclick="showVehicleDescription(${vehicle.id})">

# &nbsp;                                   <i class="fas fa-info-circle"></i> Descripción

# &nbsp;                               </button>` : 

# &nbsp;                               `<a href="https://wa.me/573137015502?text=Hola,%20estoy%20interesado%20en%20el%20${encodeURIComponent(vehicle.name)}" class="btn btn-whatsapp" target="\_blank">

# &nbsp;                                   <i class="fab fa-whatsapp"></i> WhatsApp

# &nbsp;                               </a>

# &nbsp;                               <button class="btn btn-description" onclick="showVehicleDescription(${vehicle.id})">

# &nbsp;                                   <i class="fas fa-info-circle"></i> Descripción

# &nbsp;                               </button>`

# &nbsp;                           }

# &nbsp;                       </div>

# &nbsp;                   </div>

# &nbsp;               `;

# &nbsp;               container.appendChild(vehicleCard);

# &nbsp;           });

# &nbsp;       }

# 

# &nbsp;       // Configuración de formularios

# &nbsp;       function setupForms() {

# &nbsp;           // Configuración del formulario de venta

# &nbsp;           const sellForm = document.getElementById('sellForm');

# &nbsp;           let sellAuthorization = false;

# &nbsp;           

# &nbsp;           // Validación en tiempo real

# &nbsp;           document.getElementById('sellName').addEventListener('input', validateSellForm);

# &nbsp;           document.getElementById('sellPhone').addEventListener('input', validateSellForm);

# &nbsp;           document.getElementById('sellEmail').addEventListener('input', validateSellForm);

# &nbsp;           document.getElementById('vehicleBrand').addEventListener('input', validateSellForm);

# &nbsp;           document.getElementById('vehicleModel').addEventListener('input', validateSellForm);

# &nbsp;           document.getElementById('vehicleYear').addEventListener('input', validateSellForm);

# &nbsp;           document.getElementById('vehicleMileage').addEventListener('input', validateSellForm);

# &nbsp;           

# &nbsp;           // Botones de autorización

# &nbsp;           document.getElementById('sellAcceptBtn').addEventListener('click', function() {

# &nbsp;               sellAuthorization = true;

# &nbsp;               this.style.backgroundColor = '#218838';

# &nbsp;               document.getElementById('sellDeclineBtn').style.backgroundColor = '#6c757d';

# &nbsp;               validateSellForm();

# &nbsp;           });

# &nbsp;           

# &nbsp;           document.getElementById('sellDeclineBtn').addEventListener('click', function() {

# &nbsp;               sellAuthorization = false;

# &nbsp;               this.style.backgroundColor = '#c82333';

# &nbsp;               document.getElementById('sellAcceptBtn').style.backgroundColor = '#6c757d';

# &nbsp;               validateSellForm();

# &nbsp;               alert('Para continuar con el proceso es necesario autorizar el tratamiento de datos personales.');

# &nbsp;           });

# &nbsp;           

# &nbsp;           // Envío del formulario

# &nbsp;           sellForm.addEventListener('submit', function(e) {

# &nbsp;               e.preventDefault();

# &nbsp;               

# &nbsp;               if (!validateSellForm()) {

# &nbsp;                   alert('Por favor completa todos los campos requeridos correctamente.');

# &nbsp;                   return;

# &nbsp;               }

# &nbsp;               

# &nbsp;               const name = document.getElementById('sellName').value;

# &nbsp;               const phone = document.getElementById('sellPhone').value;

# &nbsp;               const email = document.getElementById('sellEmail').value;

# &nbsp;               const brand = document.getElementById('vehicleBrand').value;

# &nbsp;               const model = document.getElementById('vehicleModel').value;

# &nbsp;               const year = document.getElementById('vehicleYear').value;

# &nbsp;               const mileage = document.getElementById('vehicleMileage').value;

# &nbsp;               const info = document.getElementById('additionalInfo').value;

# &nbsp;               

# &nbsp;               // Crear mensaje para WhatsApp

# &nbsp;               let whatsappMessage = `Hola, me interesa vender mi vehículo.%0A%0A`;

# &nbsp;               whatsappMessage += `\*Nombre:\* ${name}%0A`;

# &nbsp;               whatsappMessage += `\*Teléfono:\* ${phone}%0A`;

# &nbsp;               whatsappMessage += `\*Correo:\* ${email}%0A%0A`;

# &nbsp;               whatsappMessage += `\*Información del vehículo:\*%0A`;

# &nbsp;               whatsappMessage += `\*Marca:\* ${brand}%0A`;

# &nbsp;               whatsappMessage += `\*Modelo:\* ${model}%0A`;

# &nbsp;               whatsappMessage += `\*Año:\* ${year}%0A`;

# &nbsp;               whatsappMessage += `\*Kilometraje:\* ${mileage} km%0A`;

# &nbsp;               

# &nbsp;               if (info) {

# &nbsp;                   whatsappMessage += `%0A\*Información adicional:\*%0A${info}%0A`;

# &nbsp;               }

# &nbsp;               

# &nbsp;               whatsappMessage += `%0A\*Fecha:\* ${new Date().toLocaleDateString()}`;

# &nbsp;               whatsappMessage += `%0A%0A\*NOTA:\* El usuario ha autorizado el tratamiento de sus datos personales según la Ley 1581 de 2012.`;

# &nbsp;               

# &nbsp;               // Abrir WhatsApp

# &nbsp;               window.open(`https://wa.me/573137015502?text=${whatsappMessage}`, '\_blank');

# &nbsp;               

# &nbsp;               // Resetear formulario

# &nbsp;               this.reset();

# &nbsp;               sellAuthorization = false;

# &nbsp;               document.getElementById('sellSubmitBtn').disabled = true;

# &nbsp;               document.getElementById('sellAcceptBtn').style.backgroundColor = '#28a745';

# &nbsp;               document.getElementById('sellDeclineBtn').style.backgroundColor = '#dc3545';

# &nbsp;               

# &nbsp;               // Limpiar indicadores de validación

# &nbsp;               document.querySelectorAll('#sellForm .validation-message').forEach(el => {

# &nbsp;                   el.textContent = '';

# &nbsp;                   el.className = 'validation-message';

# &nbsp;               });

# &nbsp;               document.querySelectorAll('#sellForm .form-control').forEach(el => {

# &nbsp;                   el.classList.remove('input-valid', 'input-invalid');

# &nbsp;               });

# &nbsp;           });

# &nbsp;           

# &nbsp;           // Función de validación del formulario de venta

# &nbsp;           function validateSellForm() {

# &nbsp;               const name = document.getElementById('sellName').value.trim();

# &nbsp;               const phone = document.getElementById('sellPhone').value.trim();

# &nbsp;               const email = document.getElementById('sellEmail').value.trim();

# &nbsp;               const brand = document.getElementById('vehicleBrand').value.trim();

# &nbsp;               const model = document.getElementById('vehicleModel').value.trim();

# &nbsp;               const year = document.getElementById('vehicleYear').value;

# &nbsp;               const mileage = document.getElementById('vehicleMileage').value;

# &nbsp;               

# &nbsp;               // Validaciones básicas

# &nbsp;               const nameValid = name.length >= 2;

# &nbsp;               const phoneValid = /^\[0-9+\\-\\s()]{7,}$/.test(phone);

# &nbsp;               const emailValid = /^\[^\\s@]+@\[^\\s@]+\\.\[^\\s@]+$/.test(email);

# &nbsp;               const brandValid = brand.length >= 2;

# &nbsp;               const modelValid = model.length >= 1;

# &nbsp;               const yearValid = year >= 1990 \&\& year <= 2025;

# &nbsp;               const mileageValid = mileage >= 0;

# &nbsp;               

# &nbsp;               // Actualizar indicadores visuales

# &nbsp;               updateValidationIndicator('sellName', nameValid);

# &nbsp;               updateValidationIndicator('sellPhone', phoneValid);

# &nbsp;               updateValidationIndicator('sellEmail', emailValid);

# &nbsp;               

# &nbsp;               // Determinar si el formulario es válido

# &nbsp;               const formValid = nameValid \&\& phoneValid \&\& emailValid \&\& 

# &nbsp;                               brandValid \&\& modelValid \&\& yearValid \&\& 

# &nbsp;                               mileageValid \&\& sellAuthorization;

# &nbsp;               

# &nbsp;               // Actualizar estado del botón

# &nbsp;               document.getElementById('sellSubmitBtn').disabled = !formValid;

# &nbsp;               

# &nbsp;               return formValid;

# &nbsp;           }

# &nbsp;           

# &nbsp;           // Función para actualizar indicadores visuales de validación

# &nbsp;           function updateValidationIndicator(fieldId, isValid) {

# &nbsp;               const field = document.getElementById(fieldId);

# &nbsp;               const validationElement = document.getElementById(fieldId + 'Validation');

# &nbsp;               

# &nbsp;               if (isValid) {

# &nbsp;                   field.classList.remove('input-invalid');

# &nbsp;                   field.classList.add('input-valid');

# &nbsp;                   validationElement.textContent = '✓ Campo válido';

# &nbsp;                   validationElement.className = 'validation-message validation-success';

# &nbsp;               } else {

# &nbsp;                   field.classList.remove('input-valid');

# &nbsp;                   field.classList.add('input-invalid');

# &nbsp;                   

# &nbsp;                   if (fieldId === 'sellName') {

# &nbsp;                       validationElement.textContent = 'El nombre debe tener al menos 2 caracteres';

# &nbsp;                   } else if (fieldId === 'sellPhone') {

# &nbsp;                       validationElement.textContent = 'Ingresa un número de teléfono válido';

# &nbsp;                   } else if (fieldId === 'sellEmail') {

# &nbsp;                       validationElement.textContent = 'Ingresa un correo electrónico válido';

# &nbsp;                   }

# &nbsp;                   

# &nbsp;                   validationElement.className = 'validation-message validation-error';

# &nbsp;               }

# &nbsp;           }

# &nbsp;           

# &nbsp;           // Configuración del formulario de contacto (similar al original)

# &nbsp;           // ... (código similar al del formulario de venta)

# &nbsp;       }

# 

# &nbsp;       // Inicialización de la página

# &nbsp;       window.onload = function() {

# &nbsp;           loadVehicles();

# &nbsp;           setupForms();

# &nbsp;           

# &nbsp;           // Configurar filtros

# &nbsp;           document.getElementById('applyFilters').addEventListener('click', applyFilters);

# &nbsp;           document.getElementById('clearFilters').addEventListener('click', function() {

# &nbsp;               document.getElementById('filterStatus').value = 'all';

# &nbsp;               document.getElementById('filterPrice').value = 'all';

# &nbsp;               document.getElementById('filterYear').value = 'all';

# &nbsp;               document.getElementById('filterFuel').value = 'all';

# &nbsp;               loadVehicles();

# &nbsp;           });

# &nbsp;           

# &nbsp;           // Cerrar modal al hacer clic en la X

# &nbsp;           document.querySelector('.close-modal').addEventListener('click', function() {

# &nbsp;               document.getElementById('vehicleModal').style.display = 'none';

# &nbsp;           });

# &nbsp;           

# &nbsp;           // Cerrar modal al hacer clic fuera del contenido

# &nbsp;           window.addEventListener('click', function(event) {

# &nbsp;               const modal = document.getElementById('vehicleModal');

# &nbsp;               if (event.target === modal) {

# &nbsp;                   modal.style.display = 'none';

# &nbsp;               }

# &nbsp;           });

# &nbsp;           

# &nbsp;           // Smooth scroll para enlaces internos

# &nbsp;           document.querySelectorAll('a\[href^="#"]').forEach(anchor => {

# &nbsp;               anchor.addEventListener('click', function (e) {

# &nbsp;                   e.preventDefault();

# &nbsp;                   

# &nbsp;                   const targetId = this.getAttribute('href');

# &nbsp;                   if(targetId === '#') return;

# &nbsp;                   

# &nbsp;                   const targetElement = document.querySelector(targetId);

# &nbsp;                   if(targetElement) {

# &nbsp;                       targetElement.scrollIntoView({

# &nbsp;                           behavior: 'smooth'

# &nbsp;                       });

# &nbsp;                   }

# &nbsp;               });

# &nbsp;           });

# &nbsp;       };

# &nbsp;   </script>

# </body>

# </html>

