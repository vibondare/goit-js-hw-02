"use strict";

function getShippingCost(country) {
    let shippingPriceToChina = 100;
    let shippingPriceToChile = 250;
    let shippingPriceToAustalia = 170;
    let shippingPriceToJamaica = 120;

    switch (country) {
        case "China":
            return `Shipping to ${country} will cost ${shippingPriceToChina} credits`;
            break;
        case "Chile":
            return `Shipping to ${country} will cost ${shippingPriceToChile} credits`;
            break;
        case "Australia":
            return `Shipping to ${country} will cost ${shippingPriceToAustalia} credits`;
            break;
        case "Jamaica":
            return `Shipping to ${country} will cost ${shippingPriceToJamaica} credits`;
            break;
        default:
            return "Sorry, there is no delivery to your country";
    }
}

console.log(getShippingCost("Australia"));
console.log(getShippingCost("Germany"));
console.log(getShippingCost("China"));
console.log(getShippingCost("Chile"));
console.log(getShippingCost("Jamaica"));
console.log(getShippingCost("Sweden"));