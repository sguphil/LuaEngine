# LuaEngine
/**
 * usage: 
 * to export c++ class to lua follow the steps: 
 * 1.if first time, open CLuaRegFuncConfig.hpp add 
 * "DECL_CLASS_LUAHOOK" and "DECL_CLASS_REGTYPE_GETTER"; open
 * CLuaRegFuncConfig.cpp add "__DEF_CLASS_LUAHOOK_BEGIN" chuck 
 * and add "__DEF_REGTYPE_ARRAY_BEGIN" chuck, or just open 
 * CLuaRegFuncConfig.cpp add item to "__DEF_CLASS_LUAHOOK_BEGIN" chuck 
 * and add "__DEF_REGTYPE_ARRAY_BEGIN" chuck. 
 *  
 * 2.if first time, open CLuaRegNameConf.hpp add 
 * "DECL_REG_CLASS_NAME" and then open CLuaRegNameConf.cpp add 
 * "DEF_REG_CLASS_NAME" with the argv classname, or nothing to 
 * do in this step. 
 */
