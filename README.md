# unidad_3
compilacion_y_depuracion_de_codigo

#arduino_voice _master

![image](https://user-images.githubusercontent.com/79875910/114886756-6c8d7b00-9dcd-11eb-90cf-88f1a2944431.png)
                                         
  //importamos libreias como bluetooth serial el cual tendremos una comunicasion serial con equipos
  ya que despues llamamos de las librerias.


![image](https://user-images.githubusercontent.com/79875910/114886962-a2326400-9dcd-11eb-976a-2aab7512b03a.png)



 este manda a correr el programa con la variable My aps a mi pareser lo manda a llamar
 
 
 ![image](https://user-images.githubusercontent.com/79875910/114888126-96936d00-9dce-11eb-9afc-fa2ed79b5cc8.png)
 
 
en la clase podemos statewitget esta es la raiz de nuestra aplicacion.



![image](https://user-images.githubusercontent.com/79875910/114893692-93e74680-9dd3-11eb-8910-135ee6278f14.png)




estos sonobjetos en el cual le estan dando atributos d color tamañño ets pero desde la libreria widget


![image](https://user-images.githubusercontent.com/79875910/114895542-33f19f80-9dd5-11eb-87ae-da7a35c98f84.png)


comprovamos un ejemplo y modificamos algubos atributos de algunos objetos


![image](https://user-images.githubusercontent.com/79875910/114896399-ecb7de80-9dd5-11eb-81f7-c6936959fd71.png)

![image](https://user-images.githubusercontent.com/79875910/114896472-fb9e9100-9dd5-11eb-91df-d5eb18d32cdb.png)

![image](https://user-images.githubusercontent.com/79875910/114896517-06f1bc80-9dd6-11eb-939f-435bcb042073.png)


![image](https://user-images.githubusercontent.com/79875910/114896773-3acce200-9dd6-11eb-8775-ebba97bb53de.png)


![image](https://user-images.githubusercontent.com/79875910/114896572-14a74200-9dd6-11eb-90d2-85710b8d1a31.png)



















#flutter camara_de_video


![image](https://user-images.githubusercontent.com/79875910/114897267-af078580-9dd6-11eb-8ed5-8a8acec0bdfd.png)

![image](https://user-images.githubusercontent.com/79875910/114897922-4f5daa00-9dd7-11eb-8b6f-fce9153d4618.png)

![image](https://user-images.githubusercontent.com/79875910/114897963-58e71200-9dd7-11eb-8f1a-8b24b9f2ae91.png)


Enlas pruevas que realise el celular estaba desconectado al  omento de tomar una foto me marco error despues lo conecte y este me asedio omar una foto
fue porque se perdio la interfaze



#flutter_tensorflow

![image](https://user-images.githubusercontent.com/79875910/114899804-e5460480-9dd8-11eb-9eaf-ca440437662e.png)

![image](https://user-images.githubusercontent.com/79875910/114899856-f131c680-9dd8-11eb-93e5-a2471264a2e8.png)

![image](https://user-images.githubusercontent.com/79875910/114899909-fd1d8880-9dd8-11eb-8f48-730923cdfdcd.png)

![image](https://user-images.githubusercontent.com/79875910/114899953-07d81d80-9dd9-11eb-9147-70089bc7b50c.png)




#flutter_componentes_master

![image](https://user-images.githubusercontent.com/79875910/114901104-170b9b00-9dda-11eb-9352-82a8f78ea9cb.png)


![image](https://user-images.githubusercontent.com/79875910/114901164-268ae400-9dda-11eb-8308-35b1fd853bf9.png)


![image](https://user-images.githubusercontent.com/79875910/114901236-373b5a00-9dda-11eb-8b7a-89f1b9ef3875.png)


se esta iniciando la instalacion de la APK en nuestro celular

![image](https://user-images.githubusercontent.com/79875910/114902163-2d662680-9ddb-11eb-92ef-9b9496a99f69.png)


![image](https://user-images.githubusercontent.com/79875910/114903186-2986d400-9ddc-11eb-8705-8b935f8aff68.png)

![image](https://user-images.githubusercontent.com/79875910/114903239-399eb380-9ddc-11eb-88a1-d4e1f3f7a650.png)

![image](https://user-images.githubusercontent.com/79875910/114903330-50450a80-9ddc-11eb-8da2-6456ab7a8cf5.png)







#app_Master


![image](https://user-images.githubusercontent.com/79875910/114903595-939f7900-9ddc-11eb-816d-04a914e81df9.png)


![image](https://user-images.githubusercontent.com/79875910/114903737-b598fb80-9ddc-11eb-88bd-d59216684f1c.png)

![image](https://user-images.githubusercontent.com/79875910/114903779-c0ec2700-9ddc-11eb-8acf-9125b49e7509.png)

// class MyHomePage extends StatefulWidget {
//   MyHomePage({Key key, this.title}) : super(key: key);
//   final String title;
//
//   @override
//   _MyHomePageState createState() => _MyHomePageState();
// }
//
// class _MyHomePageState extends State<MyHomePage> {
//   int _currentStep = 0;
//   BluetoothDevice device;
//
//   void onStepContinue() async {
//     if (_currentStep == 0) {
//       setState(() {
//         _currentStep = 1;
//       });
//     }
//   }
//
//   void onStepCancel() {
//     if (_currentStep == 1) {
//       setState(() {
//         _currentStep = 0;
//       });
//     }
//   }
//
//   @override
//   Widget build(BuildContext context) {
//     List<Step> _steps = [
//       Step(
//         title: Text('Connection'),
//         content: Container(
//           height: 500,
//           child: SelectBondedDevicePage(
//             onCahtPage: (BluetoothDevice device) {
//               Navigator.push(
//                 context,
//                 MaterialPageRoute(
//                   builder: (context) {
//                     return ChatPage(server: device);
//                   },
//                 ),
//               );
//             },
//           ),
//         ),
//         state: StepState.editing,
//         isActive: true,
//       ),
//       Step(
//         title: Text('Led'),
//         content: Container(
//             // child: onCahtPage,
//             ),
//       ),
//     ];
//     return Scaffold(
//       appBar: AppBar(
//         title: Text(widget.title),
//       ),
//       body: Stepper(
//         steps: _steps,
//         type: StepperType.horizontal,
//         currentStep: _currentStep,
//         onStepContinue: onStepContinue,
//         onStepCancel: onStepCancel,
//       ),
//       floatingActionButton: FloatingActionButton(
//         onPressed: () {
//           //
//         },
//         tooltip: 'Increment',
//         child: Icon(Icons.search),
//       ), // This trailing comma makes auto-formatting nicer for build methods.
//     );
//   }
// }

![image](https://user-images.githubusercontent.com/79875910/114916158-13801000-9dea-11eb-84bc-7b6e046c9ed3.png)






![image](https://user-images.githubusercontent.com/79875910/114919068-6c9d7300-9ded-11eb-9b83-11914938b725.png)


aqui tenemos los APK instaladas en el celuarcelular

