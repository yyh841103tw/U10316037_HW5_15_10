import java.util.*;
class MyStack implements Cloneable {
	public ArrayList<Object> list = new ArrayList<Object>();
  //to distinguish stack empty or not
	public boolean isEmpty(){
		return list.isEmpty();
	}
  //get stack size
	public int getSize() {
		return list.size();
	}
  //peek stack
	public Object peek() {
		return list.get(getSize() - 1);
	}
  //remove the last value first
	public Object pop() {
		Object o = list.get(getSize() - 1);
		list.remove(getSize() - 1);
		return o;
	}
  //add object
	public void push(Object o) {
		list.add(o);
	}
	public String toString() {	
		return "stack: " + list.toString();
	}

	@SuppressWarnings("unchecked")
	public Object clone()  throws CloneNotSupportedException{

			MyStack STACK = (MyStack) super.clone();
			STACK.list = (ArrayList<Object>)(list.clone());

			return STACK;

		
	}
}
