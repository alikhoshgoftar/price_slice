# price_slice
you can slice your price by this component



import React from "react";
import PriceSlice from "price-slice"

export default class App2 extends React.Component{
constractor(props){
    super(props)
    this.state{price:null}
}

componentDidMount(){
    this.setState({price:PriceSlice(55326221)})
}

render(){
    return(
        <div>
            {this.state.price}
        </div>
    )

}
}
