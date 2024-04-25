# PreEntrega2ValverdeValdiviaa

DESKTOP.HTML


<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8" />
		<meta http-equiv="X-UA-Compatible" content="IE=edge" />
		<meta
			name="viewport"
			content="width=device-width, initial-scale=1.0"
		/>
		<title>Guitar Shop</title>
		<link rel="stylesheet" href="styles.css" />
	</head>
	<body>
		<header>
			<h1>Guitar Shop</h1>

			<div class="container-icon">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					fill="none"
					viewBox="0 0 24 24"
					stroke-width="1.5"
					stroke="currentColor"
					class="icon-cart"
				>
					<path
						stroke-linecap="round"
						stroke-linejoin="round"
						d="M15.75 10.5V6a3.75 3.75 0 10-7.5 0v4.5m11.356-1.993l1.263 12c.07.665-.45 1.243-1.119 1.243H4.25a1.125 1.125 0 01-1.12-1.243l1.264-12A1.125 1.125 0 015.513 7.5h12.974c.576 0 1.059.435 1.119 1.007zM8.625 10.5a.375.375 0 11-.75 0 .375.375 0 01.75 0zm7.5 0a.375.375 0 11-.75 0 .375.375 0 01.75 0z"
					/>
				</svg>
				<div class="count-products">
					<span id="contador-productos">0</span>
				</div>

				<div class="container-cart-products hidden-cart">
					<div class="cart-product">
						<div class="info-cart-product">
                            <span class="cantidad-producto-carrito">1</span>
                            <p class="titulo-producto-carrito">Zapatos Nike</p>
                            <span class="precio-producto-carrito">$80</span>
                        </div>
						<svg
							xmlns="http://www.w3.org/2000/svg"
							fill="none"
							viewBox="0 0 24 24"
							stroke-width="1.5"
							stroke="currentColor"
							class="icon-close"
						>
							<path
								stroke-linecap="round"
								stroke-linejoin="round"
								d="M6 18L18 6M6 6l12 12"
							/>
						</svg>
					</div>
                    <div class="cart-total">
                        <h3>Total:</h3>
                        <span class="total-pagar">$200</span>
                    </div>
				</div>
			</div>
		</header>
		<div class="container-items">
			<div class="item">
				<figure>
					<img
						src="img/guitarra.jpg"
						alt="producto"
					/>
				</figure>
				<div class="info-product">
					<h2>Guitarra Gibson Les Paul</h2>
					<p class="price">$250</p>
					<button>Añadir al carrito</button>
				</div>
			</div>
			<div class="item">
				<figure>
					<img
						src="img/4e64b54754a99431d632b0a6b9735d99.jpg"
						alt="producto"
					/>
				</figure>
				<div class="info-product">
					<h2>Guitarra Fender Stratocaster </h2>
					<p class="price">$300</p>
					<button>Añadir al carrito</button>
				</div>
			</div>
			<div class="item">
				<figure>
					<img
						src="img/f6bcb545ccd3081132b7306fc9cc3777.jpg"
						alt="producto"
					/>
				</figure>
				<div class="info-product">
					<h2>Bajo Fender Signature</h2>
					<p class="price">$200</p>
					<button>Añadir al carrito</button>
				</div>
			</div>
			<div class="item">
				<figure>
					<img
						src="img/8bf4a1d4853a7d186502c5e4f99d7b95.jpg"
						alt="producto"
					/>
				</figure>
				<div class="info-product">
					<h2>Amplificador Marshall MG50</h2>
					<p class="price">$150</p>
					<button>Añadir al carrito</button>
				</div>
			</div>
			<div class="item">
				<figure>
					<img
						src="img/a1a6eba65f7bb79b27e45b2df724e76c.jpg"
						alt="producto"
					/>
				</figure>
				<div class="info-product">
					<h2>Guitarra Fender Stratocaster Signature</h2>
					<p class="price">$300</p>
					<button>Añadir al carrito</button>
				</div>
			</div>
		</div>

        <script src="index.js"></script>
	</body>
</html>


MOBILE INDEX:


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guitar Shop</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="container-fluid bg-dark text-white py-3">
        <div class="container">
            <div class="row">
                <div class="col-md-6">
                    <h1 class="text-center">Guitar Shop</h1>
                </div>
                <div class="col-md-6">
                    <div class="container-icon d-flex justify-content-end">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="icon-cart">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 10.5V6a3.75 3.75 0 10-7.5 0v4.5m11.356-1.993l1.263 12c.07.665-.45 1.243-1.119 1.243H4.25a1.125 1.125 0 01-1.12-1.243l1.264-12A1.125 1.125 0 015.513 7.5h12.974c.576 0 1.059.435 1.119 1.007zM8.625 10.5a.375.375 0 11-.75 0 .375.375 0 01.75 0zm7.5 0a.375.375 0 11-.75 0 .375.375 0 01.75 0z"/>
                        </svg>
                        <div class="count-products">
                            <span id="contador-productos">0</span>
                        </div>
                        <div class="container-cart-products hidden-cart">
                            <div class="cart-product">
                                <div class="info-cart-product">
                                    <span class="cantidad-producto-carrito">1</span>
                                    <p class="titulo-producto-carrito">Zapatos Nike</p>
                                    <span class="precio-producto-carrito">$80</span>
                                </div>
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="icon-close">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/>
                                </svg>
                            </div>
                            <div class="cart-total">
                                <h3>Total:</h3>
                                <span class="total-pagar">$200</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </header>
    
    <div class="container mt-4">
        <div class="row">
            <div class="col-md-4 mb-4">
                <div class="item">
                    <figure>
                        <img src="img/guitarra.jpg" alt="producto" class="img-fluid">
                    </figure>
                    <div class="info-product">
                        <h2>Guitarra Gibson Les Paul</h2>
                        <p class="price">$250</p>
                        <button class="btn btn-dark">Añadir al carrito</button>
                    </div>
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="item">
                    <figure>
                        <img src="img/4e64b54754a99431d632b0a6b9735d99.jpg" alt="producto" class="img-fluid">
                    </figure>
                    <div class="info-product">
                        <h2>Guitarra Fender Stratocaster</h2>
                        <p class="price">$300</p>
                        <button class="btn btn-dark">Añadir al carrito</button>
                    </div>
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="item">
                    <figure>
                        <img src="img/f6bcb545ccd3081132b7306fc9cc3777.jpg" alt="producto" class="img-fluid">
                    </figure>
                    <div class="info-product">
                        <h2>Bajo Fender Signature</h2>
                        <p class="price">$200</p>
                        <button class="btn btn-dark">Añadir al carrito</button>
                    </div>
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="item">
                    <figure>
                        <img src="img/8bf4a1d4853a7d186502c5e4f99d7b95.jpg" alt="producto" class="img-fluid">
                    </figure>
                    <div class="info-product">
                        <h2>Amplificador Marshall MG50</h2>
                        <p class="price">$150</p>
                        <button class="btn btn-dark">Añadir al carrito</button>
                    </div>
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="item">
                    <figure>
                        <img src="img/a1a6eba65f7bb79b27e45b2df724e76c.jpg" alt="producto" class="img-fluid">
                    </figure>
                    <div class="info-product">
                        <h2>Guitarra Fender Stratocaster Signature</h2>
                        <p class="price">$300</p>
                        <button class="btn btn-dark">Añadir al carrito</button>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <script src="index.js"></script>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
