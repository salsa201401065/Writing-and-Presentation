# Writing-and-Presentation

## **React-Redux Counter**
- Membuat button yang dapat melakukan increment dan decrement
```html
import React from 'react';
import '../materialize.min.css'
import {connect} from "react-redux"
class CounterContainer extends React.Component {
    render() {
        const incrementAction = {type:"INCREMENT"}
        const decremnetrAction = {type:"DECREMENT"}
        const addElemenAction = {type:"ADD_ELEMENT"}
        return (
            <div className="custom-row">
                <button onClick={()=>{this.props.dispatch(addElemenAction)}}> Tambah Counter</button>
                {this.props.component.map((element ,index )=>{
                    return <div className="card-panel teal">
                        <button onClick={()=>{this.props.dispatch({...incrementAction, index : index})}} >plus</button>
                        <h1>{element}</h1>
                        <button onClick={()=>{this.props.dispatch({...decremnetrAction, index : index})}} >min</button>
                    </div>
                })}
            </div>
        );
    }
}
const mapStateToProps=(state)=>{
    return {component: state.component}
}
```

Output :

![Screenshot (237)](https://user-images.githubusercontent.com/85721113/200225294-ccb4a230-b3c4-4d4c-8b24-8bb3c04c0daf.png)


## **React-Redux Todo List**
- Untuk menghubungkan component dengan redux dapat menggunakan method connect()
- Lakukan import menggunakan
```html
import { connect } from "react-redux";
```
```html
import React, { useRef } from "react";
import { AiFillEdit } from "react-icons/ai";
import { IoCheckmarkDoneSharp, IoClose } from "react-icons/io5";

const TodoItem = (props) => {
  
  const { item, updateTodo, removeTodo, completeTodo } = props;
```
- item --> berisi data tunggal untuk todo item
- updateTodo --> Method untuk update todo
- completeTodo --> method untuk mengatur todo yang selesai
- removeTodo --> method untuk menghapus todo item



